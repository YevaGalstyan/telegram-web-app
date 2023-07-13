# Telegram Web App with Angular

This is an example project showcasing a Telegram web app built using the Angular framework.

-----
## Links
* Official docs: [Telegram Web App](https://core.telegram.org/bots/webapps)
* Telegram Demo Bot: [Durger King](https://t.me/durgerkingbot)
* Live Demo Bot: Example Bot

-----

## Getting Started

### Host Web app in [Vercel](https://vercel.com/) or GitHub pages 

To host on GitHub pages:
1. Create a repository (or fork this one)
2. On the repository: Settings > Pages:
   1. Source: Deploy from a branch 
   2. Branch: master, / (root), Save
3. Wait a few minutes for the web to be deployed. It will be available at: https://{github-username}.github.io/{repository-name}/{location-inside-repository}.

To host on Vercel:
1. Create Vercel account
2. Connect Vercel account to GitHub account
3. Import repository and deploy

### Configure User button to open web app
1. Go to [Bot Father](https://t.me/BotFather)
2. Type ```/mybots```
3. Select your bot 
4. ```Bot Settings``` — ```Menu Button``` — ```Custom/Edit menu button URL```
5. Send a URL to your Web App
6. Send custom button name if not configured

### Add script to ```index.html``` 

To connect a Web App to the Telegram client, place the script telegram-web-app.js in the <head> tag before any other scripts, using this code ([more info](https://core.telegram.org/bots/webapps#initializing-web-apps)):

````
<script src="https://telegram.org/js/telegram-web-app.js"></script>
````
Note: Don't forget to download package
-----

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial purposes.
