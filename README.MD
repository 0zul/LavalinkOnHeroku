# heroku-lavalink

![LavalinkOnHeroku](https://socialify.git.ci/IamTheRealSami/LavalinkOnHeroku/image?description=1&font=Source%20Code%20Pro&forks=1&issues=1&language=1&owner=1&pattern=Formal%20Invitation&pulls=1&stargazers=1&theme=Dark)

Now with internal pinging.

Easily deploy a lavalink server on heroku.
This is a very elementary and barebones approach, but reliable nonetheless.
This branch will automatically download the Lavalink.jar, but it may not be latest.

Current Lavalink release: **v3.3.1**

**Using Github Deploy:**
1. Create a fork of this repo
2. Navigate to your heroku project @dashboard.heroku.com
3. Navigate to your project *"Settings"*, click *"Reaveal Config Vars"*, and set a new var called *PASS* to what you want your lavalink password to be.
4. Navigate to the *"Deploy"* tab
5. Find/Click the *"Connect to GitHub"* section and login if needed
6. For the repo name, type *"heroku-lavalink"* and Click *"Search"*
7. Click *"Connect"* 
8. Scroll down and find *"Manual Deploy"*, then switch the branch to auto and *"Deploy Branch"*.

**Heroku CLI:**
1. Download files (Clone or download->Download ZIP).
2. Extract files into an empty directory.
3. Follow https://devcenter.heroku.com/articles/git.
If heroku is unable to automatically configure buildpacks, go to your projects settings on the heroku website and add java and nodejs.
4. Go to your project settings->config vars on heroku and set a new var called PASS to what you want your lavalink password to be.

**Easy Heroku Deploy Button**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/IamTheRealSami/LavalinkOnHeroku/tree/auto)

**Notes:** 
1. After changing PASS you must redeploy or click the More menu and *restart all dynos*.
2. If heroku is unable to automatically configure buildpacks, go to your projects settings on the heroku website and add java and nodejs.

