# terraform-aws-s3-bucket

A simple Terraform module to create an AWS S3 bucket.

## Usage


module "s3_bucket" {
  source  = "policy-as-code-training/s3-bucket-lb/aws"
  bucket_name = "my-bucket"
}
 