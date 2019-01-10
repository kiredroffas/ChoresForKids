Designed a web page-based application to motivate children to complete their chores. Implemented through Meteor (JavaScript,HTML,CSS) frameworks, the webpage provided the following functionalities: Parents and their children can create and modify a custom chore list, Children can individually check chores off of their created chore list when completed, Token rewards to be earned, based on the difficulty of the completed chore, token redemption available in the “store”.

In IntelliJ IDEA: cd app -> meteor npm run start -> open localhost link

Main Page: Displays logo and login system, functionalities are hidden until user logs in. Then displays links to create a chore list and to redeem rewards. Redirects to chore list/rewards page when boxes are clicked.

Chore List Page: Functional chore list (using JavaScript implementation within HTML script) can be added to, checked off, and removed from. User gains +5 coins whenever a chore is checked off of the chore list, clicking a checked off chore will uncheck and -5 coins. User's coin total is displayed at the top of the page.

Rewards Page: Displays rewards in boxes (coloring page downloads in our case, but could be replaced by anything), when rewards boxes are clicked -5 coins are taken away from user and a download to the appropriate page is issued, user's coin total is displayed at the top of the page, if user attempts to download when out of coins an error message is promted.
