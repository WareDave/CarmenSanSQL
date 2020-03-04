# CarmenSanSQL From SEI6 at GA

GA-Logo
Carmen Sandiego
We're going to use what we've learned already about searching with SQL commands, and apply it to chase down and capture an elusive and world-renowned thief, Carmen Sandiego. Figure out where Carmen's headed, so we can catch her and bring her in.

Setup
Fork and clone this repo into your homework directory.
Use the clues.sql file as your answer sheet.
Take a look at the world.sql file. See if you can figure out the steps/queries that it will perform.
Once you've reviewed that file, run the following commands:
psql -f starter-code/world.sql
Start psql and connect to the new database called world:

psql -d world
Use the \d command to see what tables are available. You should see:

world=# \d
              List of relations
 Schema |      Name       | Type  |   Owner   
--------+-----------------+-------+-----------
 public | city            | table | moonmayor
 public | country         | table | moonmayor
 public | countrylanguage | table | moonmayor
You can write queries while you're in the psql command line interface. It's hard to edit these commands in place. You can use opt + mouse click to place your cursor anywhere in your query. You can also use ctrl + c to reset your quer, or even ctrl + d to exit psql (this last shortcut only works when you're on an empty line).

Then, use the clues below to create the appropriate SQL queries to help you find Carmen and then, tell us where she's heading!!

The clues
Now, use the instructions/clues in clues.sql to complete this assignment.

Deliverable
The clues.sql file should contain your queries and answers, and should be able to run without errors. Comment out anything that's not working, but keep your attempted work available for review.

Submit homework
From your forked repo, create a New pull request.

Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
