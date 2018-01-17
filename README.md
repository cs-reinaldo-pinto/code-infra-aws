# code-infra-aws
Cloud Formation


➜  code-infra-aws git:(develop) ✗ history|grep create-stack                                                                  
 1563  aws  cloudformation create-stack --name kubernetes-tool vpc_create_cf.json
 1564  aws  cloudformation create-stack --name kubernetes-tool
 1565  aws  cloudformation create-stack --name kubernetes-tool --help
 1566  aws  cloudformation create-stack --name kubernetes-tool help
 1567  aws  cloudformation create-stack
 1568  aws  cloudformation create-stack help
 1571  aws cloudformation create-stack --stack-name kubernetes-tools --template-body file://vpc_create_cf.json
 1576  aws cloudformation create-stack --stack-name kubernetes-tools --template-body file://vpc_create_cf.json
 1582  aws cloudformation create-stack --stack-name kubernetes-tools-2 --template-body file://vpc_create_cf.yaml
 7387  aws cloudformation create-stack
 7388  aws cloudformation create-stack help
 7389  aws cloudformation create-stack --stack-name
 7390  aws cloudformation create-stack --stack-name  --help
 7391  aws cloudformation create-stack --stack-name  help
 7392  aws cloudformation create-stack  help
 7393  #aws cloudformation create-stack --stack-name myteststack --template-body file://sampletemplate.json --parameters ParameterKey=KeyPairName,ParameterValue=TestKey ParameterKey=SubnetIDs,ParameterValue=SubnetID1\\,SubnetID2\n
 7396  aws cloudformation create-stack --stack-name myteststack --template-body file://vpc.json
 7402  #aws cloudformation create-stack --stack-name myteststack --template-body file://vpc.json
 7423  #aws cloudformation create-stack --stack-name myteststackec2 --template-body file://ec2.json
 7424  aws cloudformation create-stack --stack-name myteststackec2 --template-body file://ec2.json
➜  code-infra-aws git:(develop) ✗ history|grep update-stack
 7419  aws cloudformation update-stack --stack-name myteststack --template-body file://vpc.json
➜  code-infra-aws git:(develop) ✗ history|grep describe-stack
 7400  aws cloudformation describe-stacks
 7401  aws cloudformation describe-stacks help
 7403  aws cloudformation describe-stacks --stack-name myteststack
 7404  aws cloudformation describe-stacks --stack-name myteststack  help
 7405  aws cloudformation describe-stacks --stack-name myteststack  --max-items
 7406  aws cloudformation describe-stacks --stack-name myteststack  --max-items 1
 7407  aws cloudformation describe-stacks --stack-name myteststack  --max-items 2
 7408  aws cloudformation describe-stacks --stack-name myteststack  
 7409  aws cloudformation describe-stacks --stack-name myteststack  |js
 7410  aws cloudformation describe-stacks --stack-name myteststack  |jq
 7411  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'publicsubnets|vpc'
 7412  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'publicsubnets|vpc-{0-9}'
 7413  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'publicsubnets|vpc-[0-9]'
 7414  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'subnet[0-9]|vpc-[0-9]'
 7415  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'subnet-[0-9]|vpc-[0-9]'
 7416  aws cloudformation describe-stacks --stack-name myteststack  |egrep -i 'subnet-[0-9][a-z]|vpc-[0-9]'
 7417  aws cloudformation describe-stacks --stack-name myteststack |egrep -i 'subnet-|vpc-'
 7420  aws cloudformation describe-stacks --stack-name myteststack |egrep -i 'subnet-|vpc-'
 7422  aws cloudformation describe-stacks --stack-name myteststack |egrep -i 'subnet-|vpc-'
