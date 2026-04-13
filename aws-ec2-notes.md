# AWS EC2 Notes

Till today I used to open AWS console, login, and start instance.  
Today I opened AWS as usual but I was not able to see any instance.  
So today I learned the issue was wrong region.

## Steps to connect EC2

1. Login to AWS
2. Select correct region
3. Go to EC2
4. Click Instances
5. Select instance
6. Click Connect
7. Use EC2 Instance Connect

## Check running instance

EC2 → Instances → Running

## Important

Always select correct region

## Today I learned

Earlier I struggled to create `.md` files from Git Bash.  
Today I learned how to create and commit them.

### Create .md file from Git Bash
touch file.md

### Commit from Git Bash
git add file.md
git commit -m "message"
git push