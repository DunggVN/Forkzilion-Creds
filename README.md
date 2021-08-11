# How To Deploy Forkzilion on Github Workflow
1. Copy this (Forkzilion-Creds Repo) repo link
2. Go to repo tab, click new
3. Click Import, then paste link of this repo there
4. Type the Repo Name and Choose Private Option then click Import
5. Choose Forkzilion Version:
- [Normal](https://github.com/DunggVN/Forkzilion-Workflows)
- [SuperLight](https://github.com/DunggVN/Forkzilion-Workflows/tree/pruhsuperlight)
6. Fork that repo
7. In Workflow Repo click Setting > Secrets > New repo secret
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
6. Fill the notes (whatever u want) and select these scope:
+ repo
+ workflow
7. Generate
8. Copy that token
```

10. Go to your Workflow Forked Repo and click Action > Select Workflow > Forkzilion Workflow > Run

### How to fill all vars ?
You can see some example [here](https://github.com/DunggVN/ProjectFizilion/blob/pruh/sample_config.env)

Follow me on [Github](https://github.com/DunggVN) Please 😂😂😂
