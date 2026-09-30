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

