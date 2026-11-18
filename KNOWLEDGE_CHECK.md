# Lab 09: Knowledge check

## 1. Credentials in the image?

**Your answer:** I wouldn't do this because anyone who downloads my Docker image could access my AWS credentials. This could let other people use my AWS account. Also, the credentials expire when my Learner Lab session ends, so they wouldn't work anymore.

## 2. Where did the Atlas password come from?

**Your answer:** I used my AWS credentials folder to let the container connect to AWS. Since I didn't enter the MongoDB information directly, the program got it from AWS Systems Manager. This included the MongoDB URL, username, and password.

## 3. Same tag, different image

**Your answer:** My first image ID was 1d536dc4e83f, and my new image ID was 2a9b2259a49c. This could be confusing because someone using version 0.1.0 might get a different image than before. I should have used a new version tag instead of keeping the same one.

