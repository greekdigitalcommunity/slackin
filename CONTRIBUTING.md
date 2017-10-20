## Steps for contributors

### Checking out locally
First of all, please fork the repository.  
On your local machine clone the base repo:
```bash
git clone https://github.com/greekdigitalcommunity/slackin.git
```
and set up the remotes:
```bash
git remote set-url upstream https://github.com/greekdigitalcommunity/slackin.git
git remote set-url origin <your_forks_giturl>
```

### Contributing
Now you're ready. Slackin is based on nodejs so you'll need `npm` and `node`.
You can install both with brew (if you're on a mac this should be something like `brew install node` ). Check you've got node and npm with:
```bash
npm -v
node -v
```

Make your changes in your editor of choice, commit them and open a PR.
At this stage it's good practice to let the #admin know about your changes so we all have a basic idea of what's changing and spread the knowledge between us.


### Deploying
Our slackin fork is deployed using heroku.
The login details for heroku's dashboard are available at: https://docs.google.com/spreadsheets/d/1vDAUZ4T1vdA34w1PWiMzHNZ_xF6SgNXbNn-PWTNIVl0/edit?usp=drive_web
Using these credentials you can login to http://heroku.com and manage the app's deployment by going to: https://dashboard.heroku.com/apps/greekdigitalcommunity/deploy/heroku-git

### Need help?
For more details questions/help feel free to ask in [#admin](https://greekdigitalcommunity.slack.com/messages/G5BLCHYRF)
