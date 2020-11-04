![codebuild badge](https://codebuild.us-west-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiWHlkRTgrVHRMY3d4WDdjOGdibHFuRmdsWTliTTFzeXpnTTRMd3B5Q00zMERxTzhzc1FIQlZFcjg3aTBVVnFXRUxrYTlvMHVvd0tFWTFMekl3RkxZU3p3PSIsIml2UGFyYW1ldGVyU3BlYyI6Ilg4b2VneGpsY3BnWitSdW0iLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=main)

1. Connect to GitHub on CodeBuild
2. `aws cloudformation create-stack --stack-name codebuild-test --template-body file:///Users/xinhol/Projects/codebuild-test/by-cloudformation/template.yml --capabilities  CAPABILITY_NAMED_IAM`
3. put badge to README