Provides AWS Lambda function to mirror DNS zone from on-premises DNS server to Route 53 private hosted zone. See https://aws.amazon.com/blogs/compute/powering-secondary-dns-in-a-vpc-using-aws-lambda-and-amazon-route-53-private-hosted-zones/ for more details.

The files lambda_function.py and lookup_rdtype.py have been updated to be compatible with Python 3.6 and newer.

Contains dnspython version 2.2.0 from https://github.com/rthalley/dnspython.
