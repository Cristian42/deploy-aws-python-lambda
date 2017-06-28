## Python-lambda

### https://github.com/nficano/python-lambda

#### Installation:

First, you must create an IAM Role on your AWS account called lambda_basic_execution with the LambdaBasicExecution policy attached.

From repo:
```
git clone https://github.com/Cristian42/web5
virtualenv .env
source .env/bin/activate
pip install -r requirements.txt
vi service.py
```

From scratch:
```
mkdir web
cd web
virtualenv .env
source .env/bin/activate
pip install git+https://github.com/nficano/python-lambda
lambda init
vi service.py
```

Deploy with:
```
lambda invoke
lambda deploy
```

