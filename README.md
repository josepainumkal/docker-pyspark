# docker-pyspark
A debian:jessie based Python Spark container. Used as the base image for OpenGov's PySpark setup. Installs many python dependencies such as numpy, scipy, and pandas.

## Docker Tagging Convention
The images should be tagged in the format of:

```
opengovorg/pyspark:<spark version>-<hadoop version>-<iteration>
```

where:

* \<spark version\>: The version of Spark including the major, minor, and patch
* \<hadoop version\>: The version of Spark including the major, minor, and patch
* \<iteration\>: The iteration version of this release which may include upgraded python dependency versions


## License
MIT
