# Feed Me

# GitHub
1. Set up public GitHub repo
2. Set up local git repo with the website files
3. Link local git repo to remote GitHub repo
4. Push first version of website files to GitHub repo

# Travis CI
1. Change configuration to let GitHub repo push changes to Travis CI
2. Add AWS_ACCESS_KEY and AWS_SECRET_KEY to secrets

# Website files changes
1. Make the following adjustments:
    - in /browselab/.env change the name of the 3 subdomains
    - in /browselab/.travis.yml change the name of the subdomain

# Build and deployment
1. Push changes to GitHub
2. The changes will be forwarded to Travis CI
3. Based on the .travis.yml file Travis CI will build the software and deploy it to AWS
