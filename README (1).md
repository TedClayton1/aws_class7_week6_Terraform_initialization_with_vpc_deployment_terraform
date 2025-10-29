
# AWS Class 7 Week 6 Terraform Initialization 


This project is a step by step document to assist a newcomer to Terraform in the successful downloading and initializing of a terraform directory. Lastly, it will also show what a successful deployment of a VPC looks like with 5 terraform files and images: authorization, vpc, subnets, internet gateway and nac gateways.






## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## Used By

This project is used by the following companies:

- Company 1
- Company 2


## Support

For support, email fake@fake.com or join our Slack channel.


## Tech Stack

**Client:** Terraform CLI, GitBash, Powershell, Git, and AWS CLI

**Server:** AWS Cloud Platform, AWS Provider APIs, AWS Security and Identity Services


## Deployment

To deploy this project run

```bash
  1. choco list (To download Terraform)
  2. Login to GitBash as an Administrator
  3. terraform --version
  4. curl https://raw.githubusercontent.com/aaron-dm-mcdonald/Class7-notes/refs/heads/main/101825/check.sh | bash
  5. ls -a 
  6. mkdir week6stepbystep
  7. cp./.gitignore week6stepbystep
  8. cd week6stepbystep
  9. ls -a 
  10. touch 0-auth 1-vpc.terraform
  11. ls -al
  12. code./
  13. terraform fmt 0-auth.terraform
  14. terraform init
  15. aws sts get-caller-identity 
```


## Screenshots

https://bucketweek6awshomework.s3.us-east-1.amazonaws.com/week6homework-terraforminit.PNG

