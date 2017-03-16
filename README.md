# uh rappa fo zappa
A Continuous Integration (CI) Wrapper built around [Zappa](https://github.com/Miserlou/Zappa)

Leverages Travis CI and Github API to trigger testing, coverage, VCS tagging, staging, and serverless deployment tasks 
in response to developer defined events e.g. VCS Commit, Manual Triggering, etc.

Features a servable admin interface.

### Requirements
python 2.7.13+ [download](https://www.python.org/downloads/)

> #####What about python3? 
> Short Answer: AWS lambda does not support it yet. 
>
> You can go [to this AWS forum post](https://forums.aws.amazon.com/thread.jspa?threadID=230765) to voice your support for python3. 
> Zappa does not support python3 until AWS does. See [issue 6](https://github.com/Miserlou/Zappa/issues/6).

Add these to a [virtualenv](https://github.com/pypa/virtualenv) - see requirements.txt
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
