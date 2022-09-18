## Online Shopping

The brief was to develop a static front end project with a minimum of three separate page areas using HTML and CSS while following UX industry conventions. This is an online shopping platrom for making super easy the shopping market.

<a href="https://ray-yar.github.io/online-shopping/" target="_blank">Visit the live project here</a>

![alt text](.docs/multi_platform.png "Responsive Image") 

Online Shopping is a general platform for every one who can access it throw internet and deal any thing they want. Our goal is to provide save and reliable space for users.Our aim is to make easy the market of shopping just by one click. Online Shopping platfrom is the first market place in Afghanistan. It provides a safe space for users to deal every thing which exist here or even they have their own in home.

**This website is made up of the following pages:**
1. Home Page
2. More Products Page
3. Contat Us Page

**The main objectives for establishing an online platform are:**
1. Promoting a service or product online.
2. Selling a service or product.
3. Providing product support or customer service.
4. Providing corporate information.
5. Establishing brand awareness and corporate identity.

**These users are looking for:**
1. Their favorite product which is listed in products page.
2. Cartting and then purchase their favorite product.
3. A safe and reliable area for making their deals.
4. Guarantee items which are listed in website.
6. A user fiendly interface for searching their favorite product.

## UX/UI
For UX strategy first started to think about the strategy for this website and defined who the target users would be and what features/technologies they would want. My strategy for the site was to provide reputable content and ease of access to users trying to attain information by utilising key UX principals.

**Ideal users of this website:**
1. Sellers who want to sell their products.
2. Buyers who want to buy new products.
3. Managers who are managing the activities during the deals.
4. Admin who is the owner of this website.  

**User stories:**
1. **As a new visitor:** I want to easily navigate the site to find whether the products are right fit for my needs.
2. **As a business/home owner:** I would like to find whether the products are trustworthy and reputable by seeing what the previous clients say about them.
3. **As a new visitor:** I would like to learn more about their product delivary, so I can get to know their background better. 
4. **As a new visitor:** I would like to know the dealing process and approach to their clients.
5. **As an interested client:** I want to be able to contact the owner of the site.
6. **As a potential client:** I would like to learn more about the dealer works and get validation via their history and presence in the social media. It is more reassuring to trust businesses who have a solid follower base.
8. **As a returning visitor to the website:** I want to be able to find the contact page easily to reach the managers.

**Scope**

In order to achieve the desired user & business goals, the following features will be included in this release:

1. Header and menu bar, to navigate to various sections of the page
2. About us for detailing users about the website.
3. Adding a saperate products page that users could find many various things they want.
4. Information for each product include name, price, date, descriptions.
5. Contact Us page for contacting with managers

## Features

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
