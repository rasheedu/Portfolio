Hi.
This is my clone and modification of KeystoneJS, an open source CMS.
I intend for this to be used as a basis for your portfolio.
Much of the documentation is on the Keystone website. I modified it so that you can set your username in the .env file.

#Deploying.
I deployed to heroku and these are the settings I used. I made sure to add the .env file to my .gitignore before pushing to git. To deploy to production, you should 

```
git checkout production
git commit -am "message"
git push heroku production:master
```

#Adding items to your home page.
You can log in by adding /keystone/signin to the main url. Then in a section title portfolio, you can add as much items as you want and they will be automatically populated on your home page. Good luck.