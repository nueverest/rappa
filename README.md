# uh rappa fo zappa
A Continuous Integration (CI) Wrapper built around [Zappa](https://github.com/Miserlou/Zappa)

Leverages Travis CI and Github API to trigger testing, coverage, VCS tagging, staging, and serverless deployment tasks 
in response to developer defined events e.g. VCS Commit, Manual Triggering, etc.

Features a servable admin interface.

# Requirements - see requirements.txt.
python 2.7.13+ or python 3.4+ [download](https://www.python.org/downloads/)

Add these to a [virtualenv](https://github.com/pypa/virtualenv)
* [flask](https://github.com/pallets/flask)
* [flask-s3](https://github.com/e-dard/flask-s3)
* [blowdrycss](https://github.com/nueverest/blowdrycss)
* [zappa](https://github.com/Miserlou/Zappa)
* [tox](https://github.com/tox-dev/tox)
* [tox-travis](https://github.com/ryanhiebert/tox-travis)
* [pygithub](https://github.com/PyGithub/PyGithub)
* [travispy](https://github.com/menegazzo/travispy)

Setup AWS
* Create or Login to AWS account
* Generate AWS access key with appropriate permissions
* Create or Pick an AWS S3 bucket
