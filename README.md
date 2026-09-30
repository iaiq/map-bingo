# map-bingo

I created this tool when I got a bit carried away trying to use Google Gemini to create map bingo cards to use with my Scout troop.

If you don't know map bingo is a game where you give people a 6 figure grid reference (UK Ordnance Survey maps) which they lookup and match to a feature (often an icon) on their bingo card. This should help Scouts (or others) recognise the symbols and get better at using grid references.

To play the game you need:
- As many copies of the relevant OS map as you have groups.
- A list of features and their grid references for the given map.
- Bingo cards which contain a reasonably random subset of the features.

To prepare for the game somebody need to prepare the list of features and grid references for the relevant map.

The tool has been "vibe-coded" with Gemini so I can't vouch for the quality of the code, so use at your own risk.
In its defence it is written to be self contained so you can download it and use it without a connection to the internet, helpful in lots of Scouting locations.
When you put feature data (grid references) into the app it uses "local-storage" and allows you to export a (json) file (which is human readable). You can then import the map if you have an issue with "local-storage" due to browser updates and share the details for that map with others.

## Basic Usage Instructions

1. Download the app.
2. Use the "+ New Map" button to add the map you want to use, suggest you include the map number.
3. Go to "Manage Maps" select the features you want to use and ensure any you don't want at deselected.
4. Enter the appropriate grid references for the features. Once you have done this I suggest you use the "Export Map" option to save the map config as a file.
5. Now you can use "Bingo Cards" to choose the number of cards you want and print them.
6. You can then choose to use the tool to play the game use a more manual approach.
7. If you want a zero technology option go to "Manage Maps" and use "Print Leader Sheet" which will give you a sheet with all the features and grid references to call out.
8. If you want to trust in some minimal technology go to "Game Play (GM)" this provides a screen which shows each of the grid references in a large font and a random order. You manually progress by clicking "Next Feature". At any point you can switch to "Manage Maps" and see which features have been shown, there is also a "Reset Game Progress" button here.

## Other notes

You can include grid references for all the features and only select those which you want to appear on the bingo cards.
The icons are all created as SVGs by Google Gemini it has done a better job with some than others.
It is my intention to share some map files as a library, contributions from others would be welcome.

