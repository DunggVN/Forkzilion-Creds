# How To Deploy Forkzilion on Github Workflow
1. Choose Forkzilion Version:
- [Normal](https://github.com/DunggVN/Forkzilion-Creds)
- [SuperLight](https://github.com/DunggVN/Forkzilion-Creds/tree/pruhsuperlight)
2. Copy this link: https://github.com/DunggVN/Forkzilion-Creds
3. Go to repo tab, click new
4. Click Import, then paste link of this repo there
5. Type the Repo Name and Choose Private Option then click Import
6. Go to Workflows Repo:
- [Here](https://github.com/DunggVN/Forkzilion-Workflows)
7. Fork that repo
8. In Workflow Repo click Setting > Secrets > New repo secret
9. Create 4 Secret: CREDS, GH_NAME, GH_MAIL, GH_TOKEN
10. Value:
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

11. Go to your Workflow Forked Repo and click Action > Select Workflow > Forkzilion Workflow > Run

### How to fill vars in config.env ?
You can see some example [here](https://github.com/DunggVN/ProjectFizilion/blob/pruh/sample_config.env)
- Notes:
+ Don't fill vars on that file 😂😂😂

## Credits
- Thanks to [@AbOuLfOoOoOuF](https://github.com/AbOuLfOoOoOuF) for Forkzilion Userbot
- Thanks to [@Pewdeadcake](https://github.com/Pewdeadcake) for Test Github Deploy Repo
- Thanks to [@TechiError](https://github.com/TechiError) for Original Github Deploy Repo
