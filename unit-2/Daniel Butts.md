**Chosen Project:** TBD
**Project Github:** TBD
**Deployed URL:** TBD

### First Project Proposal Idea

A social contact aggregator that lets you see and manage your contacts from various social platforms (facebook, linkedin, google, etc.).

**What problem does your project solve?**

So friends use google+ (just kidding), some use facebook, some use linkedin. Pulling all those together and seeing them centrally might be handy and help you navigate the complex online world. (as a stretch we might implement messaging to those contacts through the various APIs)

**How will your project solve this problem?**

We will connect to several social platforms and pull contacts and store them locally in a database. The app will provide a mechanism for a user to link identities across platforms.

**What web APIs will it use?**

Google OAuth, Linkedin OAuth (possibly Facebook OAuth as a stretch)

**What technologies will it use?**

Node, Express, Knex, Postgres, Handlebars, Bootstrap, Passport


---

### Second Project Proposal Idea
A recipe search app (how original... but wait!) that allows the user to record the contents of their fridge/cupboard and search for recipes based on what they actually have in stock, either through the web or a collection of favorite recipes/recipe sites.

**What problem does your project solve?**
"What do you want for dinner? We have X, Y and Z in the fridge."
"I don't know WTF to make with those ingredients."
"Me neither. Let's order pizza instead."

**How will your project solve this problem?**
We will provide a database for the user to store and update their current inventory of ingredients. They will then be able to use the app to query recipe sites on the web to provide recipes that use the ingredients they want from the database - or a "Do you feel lucky?" search that randomly selects ingredients from their inventory.

To limit recipes that include too many ingredients that they may not have, once the query is made with the desired ingredients the app will filter or provide a weighted sort of recipes that most closely match the user's stored ingredient inventory.

**What web APIs will it use?**
There are many popular recipe APIs such as Yummly that should work well. More research will be needed to choose one or decide if multiple are needed.

**What technologies will it use?**
Node, Express, Knex, Postgres, Handlebars, Bootstrap
