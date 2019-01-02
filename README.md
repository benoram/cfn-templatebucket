# cfn-templatebucket
CloudFormation template for creating a template bucket. This bucket can be used as a repository for CloudFormation templates across multiple accounts.

## Dependencies
None

## Parameters

### BucketName
The name of the bucket that will be created and managed by the script. This name must be globally unique, just like any other S3 bucket name.

```Example: companyname-cfn```

### AccountIds
A comma delimted list of account ids that will be able to read/write/access the bucket.

```Example: 111122223333,222233334444,333344445555```

