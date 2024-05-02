## s3_static_web

## This Terraform Code will create S3 bucket and hosts static website to subdomain.
 
 # You have to provide bucket_name, subdomain_name and zone_id from your domain:
  
 ```hcl
module "s3_static_web" {
  source  = "smbek/s3_static_web/aws"
  version = "0.0.4" # make sure you input last version
  # insert the 4 required variables here
  region = "us-east-2"
  bucket_name = ""
  subdomain_name = ""
  zone_id = ""

}

  ```
  # In my code provided simple restaurant menu in index.html and error.html you have to provide your own index.html and error.html