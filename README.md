# Oracle Clound Infrastructure (OCI) Stremaing Service client

This is an example of a control plane and data plane operations of OCI streaming service using Python SDK. For the puspose of this example, Python 3.9 was used.


## Downloading and Installing the SDK

You can install the Python SDK through the Python Package Index (PyPI), GitHub, OCI Resource Manager or yum on Oracle Linux.

### Set up a virtual environment

It is recommended that to run the [OCI SDK ](https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/pythonsdk.htm)in a virtual environment with [virtualenv](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/). This allows you to isolate the dependencies for the SDK and avoids any potential conflicts with other Python packages which may already be installed (e.g. in your system-wide Python).

With Linux, virtualenv is usually in a separate package from the main Python package. If you need to install virtualenv, use pip install virtualenv. To create and activate a virtual environment:

```
virtualenv <environment name>
source <environment name>/bin/activate
```
For example:
```
virtualenv oci_sdk_env
source oci_sdk_env/bin/activate
```

### PyPi

To install from PyPI use the following command:
```
pip install oci
```


### GitHub

To install from GitHub:

1. Download the SDK from [GitHub](https://github.com/oracle/oci-python-sdk/releases). The download is a zip containing a whl file and documentation.
2. Extract the files from the zip.
3. Use the following command to install the SDK:
```
pip install oci-*-py2.py3-none-any.whl
```
#### Note
If you’re unable to install the whl file, make sure pip is up to date. Use pip install -U pip and then try to install the whl file again.


## Usage
```
python stream_example.py <compartment id>
```
