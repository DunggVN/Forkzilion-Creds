# How To Deploy Forkzilion on Github Workflow
1. Go to [Workflow Repo](https://github.com/DunggVN/forkzilion-wf-example)
2. Fork that repo
3. Copy this (Forkzilion-Creds Repo) repo link
4. Go to repo tab, click new
5. Click Import, then paste link of this repo there
6. Type the Repo Name and Choose Private Option then click Import
7. Now go to Workflow Repo then click Setting > Secrets > New repo secret
8. Create 4 Secret: CREDS, GH_NAME, GH_MAIL, GH_TOKEN
9. Value:
```
CREDS = Link of The Repo you Imported
Make Sure:
+ You Removed https://
+ It's private repo
+ You changed the value in config.env
GH_NAME = Your Github Username
GH_MAIL = Your Github Email
GH_TOKEN = Your Github Personal Access Token
How to take Personal Access Token:
1. Out this repo
2. Go to Setting
3. Go to Developer Setting
4. Click Personal Access Token
5. Generate new token
6. Fill the notes (whatever u want) and select
```

10. Go to your Workflow Forked Repo and click Action > Select Workflow > Forkzilion Workflow > Run

Follow me on [Github](https://github.com/DunggVN) Please 😂😂😂
