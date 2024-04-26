## s3_static_web

## This Terraform Code will create S3 bucket and hosts static website to subdomain.
 
 # You have to provide tfvars file and zone_id from your domain:
  
 ```hcl

  region = "us-east-2"
  bucket_name = ""
  subdomain_name = ""
  zone_id = ""

  ```
  # In my code provided simple restaurant menu in index.html and error.html you can upload your own index.html manually from S3 bucket. 