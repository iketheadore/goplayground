# DNS resolve

## Pre requirements

Go has been installed and GOPATH environment variable has been set.

## Install

Move the resolve folder into GOPATH/src dir, then:

```bash
cd resolve
go install
```

If the $GOPATH/bin is not in the PATH environment, use the following command to add it:

```bash
export PATH=$PATH:$GOPATH/bin
```

## Run script

```bash
cat $domain_file | resolve
```

