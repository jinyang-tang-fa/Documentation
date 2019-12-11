## CPS master development


Here is the cicd stack that we deployed our master branch (`Tier` is `development`) to aws: [cps-cicd-master-development](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/stackinfo?filteringText=development&filteringStatus=active&viewNested=true&hideStacks=false&stackId=arn%3Aaws%3Acloudformation%3Aus-west-2%3A576861690619%3Astack%2Fcps-cicd-master-development%2F9a798350-184b-11ea-afe7-0a92bf2e649c), it helps us automatically deploy our template [cps-master-development](https://us-west-2.console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/stackinfo?filteringText=development&filteringStatus=active&viewNested=true&hideStacks=false&stackId=arn%3Aaws%3Acloudformation%3Aus-west-2%3A576861690619%3Astack%2Fcps-master-development%2Facbe5f80-184c-11ea-b076-02d0bd2cd418), which contains all needed stacks including 

1. Checkout the master branch of CPS code base
```bash
	git clone https://github.com/FutureAdvisor/CPS.git
```

2. Open `IntelliJ IDEA`, 