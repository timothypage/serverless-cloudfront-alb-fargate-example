# CloudFront -> ALB -> Fargate

## up and running

copy `environment-example.yml` to `environment.yml` and fill out with your specific variables

## assumptions

 - DOMAIN is managed in Route53
 - certificate with wildcard subdomain has already been created in ACM (Its probably easiest to do this manually and copy arn into your environment.yml)
