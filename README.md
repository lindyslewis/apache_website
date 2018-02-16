# Basic Apache website


# deploy.sh

- calls aws cloudformation create-stack
- passes in the CloudFormation template JSON file

# apache_website_cf_template.json

 - LaunchConfig with UserData
 - UserData installs and runs apache; clones this repo (gets index.html)
 - ASG of size 1

# index.html

 - Basic webpage with HTML/CSS formatting
