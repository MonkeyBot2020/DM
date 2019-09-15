<h2>DM</h2>
A virtual Dungeon Master (DM) bot for Dungeons & Dragons games on Slack. Can be included into threads, allows users to easily roll dice, make attack rolls, skill checks, store character information and more! I've used this for my own PbP games for nearly a year. It's updated regularly. 
</br></br>
<b>Relevant functions & abilities:</b>
<li>Threaded message inclusion: bot can be included into threaded messages, making dice rolls and skill checks a breeze</li>
<li>Intuitive & easy-to-use functions: players can use intuitive, fast commands to roll skill ckecks, saves and attacks</li>
<li>Initiative tracking & turn automation: DMs and players can track the turns, health, and effects of players and monsters alike in combat, with full-featured automation! Make an attack or cast a spell in a single command, and all saves, AC checks, and damage will be automatically resolved!</li>
<li>Store character information: relevant character abilities and stats can be stored easily using simple commands</li>
</br>
<b>…and more, with new features added regularly! (Coming soon: Character Sheet Import, 5e Lookup/Integration)</b> </br></br>
<b>CLICK HERE TO INSTALL BOT INTO SLACK WORKSPACE:</b> </br>
https://slack.com/oauth/authorize?client_id=655746628819.668861725555&scope=bot
</br></br>
<b>Usage:</b>
</br>
<code>@DM roll NdX+Y</code> [where N is the number of dice, X is the dice type (d20, d10, d6, d4) and Y is the bonus]</br>
<code>@DM roll NdX+Y, AdB+C</code> [multiple rolls can be done simultaneously, each roll separated by a comma]</br>
<code>@DM roll <SKILL> check</code> [where <SKILL> (without brackets) is your relevant skill]</br>
<code>@DM roll initiative</code> [automatically rolls your initiative; note that you need to record your Dex score prior]</br>
</br>
<code>@DM record <STATS></code> [where <STATS> is the following: Name: Jane Doe, Points: 27, STR: 8, DEX: 8, CON: 8, INT: 8, WIS: 8, CHA: 8, AC: 10, HP: 0, Skills: blah, blah (note: stats are CaSe sensitive)]</br>
<code>@DM record user:USER_ID HP:USER_HP</code> [where HP is the target user's health points]</br>
</br>
<code>@DM show stats</code> [will show your stats]</br>
<code>@DM show character</code> [will show your stats]</br>
<code>@DM show HP</code> [will reveal everyone's HPs]</br>
</br>
<code>@DM end turn</code> [ends your turn and moves to the next player]</br>
<code>@DM show turn order</code> [will reveal the turn order]</br>
<code>@DM next turn</code> [will progress the turn order]</br>
<code>@DM previous turn</code> [will reverse the turn order]</br>
<code>@DM reset encounter</code> [will reset the encounter]</br>
</br>
<code>@DM record main_hand: <WEAPON></code> [equip weapon in main hand, two-handed weapons will automatically be equipped in both hands]</br>
<code>@DM record off_hand: <WEAPON></code> [equip weapon in off hand]</br>
<code>@DM attack</code> [make standard attack rolls with main & off hand weapons or make unarmed attack rolls]</br>
