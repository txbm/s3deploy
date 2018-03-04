s3deploy
=========

[![Latest Version](https://img.shields.io/pypi/v/s3deploy.svg)](https://pypi.python.org/pypi/s3deploy/)
[![Build Status](https://travis-ci.org/petermelias/s3deploy.svg?branch=master)](https://travis-ci.org/petermelias/s3deploy)
[![Montly Downloads](https://img.shields.io/pypi/dm/s3deploy.svg?month=)](https://pypi.python.org/pypi/s3deploy)
[![Download format](https://img.shields.io/pypi/format/s3deploy.svg)](https://pypi.python.org/pypi/s3deploy/)
[![Coverage Status](https://coveralls.io/repos/petermelias/s3deploy/badge.png?branch=master)](https://coveralls.io/r/petermelias/s3deploy?branch=master)
[![License](https://img.shields.io/pypi/l/s3deploy.svg)](https://pypi.python.org/pypi/s3deploy/)


Deploy static sites to S3 with a single command. Efficient, fast, simple.


### Usage

#### CLI Interface

```bash
$> s3deploy --overwrite --config ~/s3deploy.config.yaml ~/my-static-site
```

That's it.

#### Installation:

```bash
$> pip install s3deploy
```

Notes:

- Omit the ```--overwrite``` option if you don't want to erase the bucket.
- If you name the config file ```s3deploy.config.yaml``` and run the binary from the CWD where that file is present, s3deploy will find it automatically.
- You must have a config file to run s3deploy: ```aws_key```, ```aws_secret```, ```bucket_name``` must all be set.
