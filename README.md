# rappa
A Continuous Integration (CI) Wrapper built around [Zappa](https://github.com/Miserlou/Zappa)

Leverages Travis CI and Github API to trigger testing, coverage, VCS tagging, staging, and serverless deployment tasks 
in response to developer defined events e.g. VCS Commit, Manual Triggering, etc.

Features a serverless admin interface.

# requirements - see requirements.txt for most up-to-date list.
python 2.7.13+ or python 3.4+ [download](https://www.python.org/downloads/)
[flask](https://github.com/pallets/flask)
[flask-s3](https://github.com/e-dard/flask-s3)
[blowdrycss](https://github.com/nueverest/blowdrycss)
[zappa](https://github.com/Miserlou/Zappa)
[tox](https://github.com/tox-dev/tox)
[tox-travis](https://github.com/ryanhiebert/tox-travis)
[pygithub](https://github.com/PyGithub/PyGithub)
[travispy](https://github.com/menegazzo/travispy)
AWS account
AWS access key with appropriate permissions
AWS S3 bucket

# desired but optional
[virtualenv](https://github.com/pypa/virtualenv)