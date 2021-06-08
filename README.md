# final-fantasy-14-notes
 Using Express, ejs layouts, bootstarp and sequelize I will use the Final Fantasy 14 API to allow users to parse their character data and add notes to specific classes, delete any notes they want, create generalized notes for overall goals and create bulleted lists in case they need further organization or are creating gear lists of items to collect. I will use a sequelize database to store their notes, as well as their parsed character data. The user would be able to search their character by providing its name and the server the character is created on. I would also like completed goals to offer an option to delete the note, or simply make it unselectable and have a line through it to mark it as comopleted, lightening the color as signification.
 
 This will use the FF14 API and the link to my brainstorm is here: https://miro.com/app/board/o9J_lAVeiYM=/
 
 This link shows example data pulled using the API for my character: https://xivapi.com/character/29244989
 
 Stretch goals would be to allow color coding based on importance, allow the user to create sub goals(milestones) along the way to reaching the main goal (dropdown menus for organization) and highlighting of specific portions that are important to the user.
 
 Roadblocks are going to be doing the requisite research to be able to link the user created notes back to the individual classes and utilizing the pulled API data properly
