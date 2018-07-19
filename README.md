# CloudStack Non OSS Libs

This repository holds the non OSS libraies required to build [CloudStack](https://github.com/apache/cloudstack)
with the maven flag `-Dnoredist`.

## Installation

In order to install the libraries into your local maven repository, simply run:

```bash
./install-non-oss.sh
```

Then you'll be able to [build CloudStack](https://github.com/apache/cloudstack/blob/master/INSTALL.md#building) from scratch:

```
mvn install -P developer -P systemvm -Dsimulator -Dnoredist
```
