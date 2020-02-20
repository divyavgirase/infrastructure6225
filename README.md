# infrastructure
#Author
Divya Vijendra Girase

#Steps To Create VPC

**Step1 - Validate Template**
aws cloudformation validate-template --region {region_name} --profile {profile_name} --template-body {file_name}

**Step2 - Update parameter file**
Update parameter.json with appropriate parameter values

**Step3 - Create Stack**
aws cloudformation create-stack --stack-name {stack_name} --region {region_name} --profile {profile_name} --template-body {file_name}

**Step To Delete Stack**
aws cloudformation delete-stack --stack-name {stack_name}

