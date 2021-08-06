# How To Deploy Forkzilion on Github Workflow
1. Go to [Workflow Repo](https://github.com/DunggVN/forkzilion-wf-example)
2. Fork that repo
3. Copy this (Creds Repo) repo link
4. Go to repo tab, click new
5. Click Import, then paste link of this repo there
6. Type the Repo Name and Choose Private Option then click Import
7. Now go to Workflow Repo then click Setting > Secrets > New repo secret
8. Create 4 Secret: CREDS, GITHUB_NAME, GITHUB_MAIL, GITHUB_TOKEN
9. Value:
```
CREDS = Link of The Repo you Imported (Remove https://)(Make sure it's private)(Change the values of config.env)
GITHUB_NAME = Your Github Username
GITHUB_MAIL = Your Github Email
GITHUB_TOKEN = Your Github Personal Access Token
```

Go to your Workflow Forked Repo and click Action > Select Workflow > Forkzilion Workflow > Run

Follow me on [Github](https://github.com/DunggVN) Please 😂😂😂

Credits:- @DunggVN

TG:- [Link Soon]()
