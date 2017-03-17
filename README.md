### wedding

Edit code, save

```
git add -u
git commit -am "Message"
```

### Deploying
Full instructions here: https://firebase.google.com/docs/hosting/deploying

You may need to install npm and for the options make sure to select folder and not `public` to deploy. Other settings can just choose default.
First option, make sure to choose hosting for deployment and not database setup.

```
npm install -g firebase-tools
firebase init
firebase deploy
```
