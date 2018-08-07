# project-group-divider

This is a small little one page web page app that helps you divide a list of names into a groups of a size you specify.  You can either add new list of names via the form on the page, or you can download this file and edit the javascript to include the list of names and group sizes you want.

Features include a seed value for the randomizer that can be set, or a random one can be generated each time you divide the groups.

After each group is split up, the randomizer is reset to the intial seed value so that as long as you have the same list of names, group size, and seed number the program will always generate the same result no matter if there now many total classes you have or what order you have them in when the program is run.

There is a checkbox that lets you to choose to divide the list of names into groups of size `X and X-1` (divide down) or `X and X+1` (divide up) if the list of names does not divide evenly into groups.

If the groups cannot be divided into groups by those restrictions, the program will automatically lower the group size until it can divide the list of names.

Custom Random function with Seed code taken from here:
https://stackoverflow.com/questions/521295/seeding-the-random-number-generator-in-javascript
By: Remco Kranenburg

Styling done by Emma Nelson
