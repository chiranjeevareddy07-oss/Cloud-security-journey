Here is the cleaned-up Commands Used – Week 2 section with the “remove #” text removed and the URLs converted back to plain CLI commands:

Commands Used – Week 2
S3
aws --endpoint-url=http://localhost:4566 s3 mb s3://my-first-bucket

aws --endpoint-url=http://localhost:4566 s3 ls

IAM
aws --endpoint-url=http://localhost:4566 iam create-user --user-name test-user

aws --endpoint-url=http://localhost:4566 iam list-users

aws --endpoint-url=http://localhost:4566 iam attach-user-policy \
  --user-name test-user \
  --policy-arn arn:aws:iam::aws:policy/AmazonS3ReadOnlyAccess

aws --endpoint-url=http://localhost:4566 iam list-attached-user-policies \
  --user-name test-user


This version is cleaner, uses proper AWS CLI formatting, and is ready to include in your Week 2 lab notes, GitHub README, or learning journal.
