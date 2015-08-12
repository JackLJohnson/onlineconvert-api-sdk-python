# Online Convert API version 2 Python SDK

This SDK provides a code base to interact with the API version 2 for [Online-Convert.com](http://www.online-convert.com/).

Since the API version 2 follows the [Swagger specs](http://swagger.io/), this code has been generated using the [swagger code generator](https://github.com/swagger-api/swagger-codegen), based on the current [API version 2 schema](https://api2.online-convert.com/schema).

## Requirements
Python 2.7 and later.
Before using the SDK, a valid account at [Online Convert](http://www.online-convert.com/) is needed in order to get an API key.

## Features
  - The SDK allows to make file conversions using the [Online-Convert.com](http://www.online-convert.com/) API.
  - Provides an interface to interact with the REST API.

## Report errors/bugs
If you find any errors in the SDK, please report them to us ([time2help@online-convert.com](mailto:time2help@online-convert.com)). 

## Contributing
We accept contributions to the SDK. To contribute, please submit your pull request to the dev branch. 

## Setuptools
You can install the bindings via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install
```

You can also install it from Github via pip:

```sh
pip install git+https://github.com/geekerzp/SwaggerPetstore-python.git
```

To use the bindings, import the following pacakge:

```python
import SwaggerPetstore
```

## Manual Installation
If you do not wish to use the setuptools, you can download the latest release.
Then, to use the bindings, import the package:

```python
import path.to.SwaggerPetstore-python.SwaggerPetstore
```



## Tests

(Make sure you are running the test inside a [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/)).

You can run the tests in the current python platform:

```sh
$ make test
[... magically installs dependencies and runs tests on your virtualenv]
Ran 7 tests in 19.289s

OK
```
or

```
$ mvn integration-test -rf :PythonPetstoreClientTests
Using 2195432783 as seed
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 37.594 s
[INFO] Finished at: 2015-05-16T18:00:35+08:00
[INFO] Final Memory: 11M/156M
[INFO] ------------------------------------------------------------------------
```
If you want to run the tests in all the python platforms use the following call:

```sh
$ make test-all
[... tox creates a virtualenv for every platform and runs tests inside of each]
  py27: commands succeeded
  py34: commands succeeded
  congratulations :)
```

