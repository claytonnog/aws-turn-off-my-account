# AWS, Turn off my Account, please 

Lambda stack to turn off and destroy all resources from your personal AWS Account to avoid billing surprises

## Resources Roadmap

* EC2 
* ALB, ELB, NLB
* RDS
* DocumentDB
* NAT Gateways

## Installation

### Using Serverless Framework 

* Clone this repo 

```bash
cd $GOPATH/src
git clone https://github.com/msfidelis/aws-turn-off-my-account.git
cd aws-turn-off-my-account
```

* Edit your preferences in `configs/prod.yml` and customize your cron rate on `serverless.yml`

* Deploy 

```bash
make deploy 
```

### Using console 

> Guenta ae 


### TODO

* Release ZIP 

* Console setup 

* Cloudformation Setup

* Tests 
