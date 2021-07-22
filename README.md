# Stati-Documentation
For support and discussion about the bot, visit out discord server [here](https://discord.gg/c4Bg7Bw7B4). You can add the bot [here](https://discord.com/api/oauth2/authorize?client_id=854781625236848640&permissions=379968&scope=bot)

## Counter Strike: Global Offensive Commands

### `g/csgostats <user>`

Fetches stats from a player. Valid items for `user` is the Steam ID (string of numbers) or your steam profile link name (https://steamcommunity.com/id/**yourlinkname**/).
![csgostats example image](/assets/csgostats_example1.png)

### `g/csgoguns <user> [category]`

Fetches gun stats from a player. Valid items for `user` is the Steam ID (string of numbers) or your steam profile link name (https://steamcommunity.com/id/**yourlinkname**/). Valid `category` options are `all`, `pistol`, `rifle`, `smg`, and `heavy`. 

Note: the following guns are categorised together in terms of stats (this is how Steam handles it)
- USP-S + P2000
- M4A4 + M4A1-S
- Desert Eagle + R8 Revolver
- MP7 + MP5SD
- TEC-9 + CZ75 Auto
- Five Seven + CZ75 Auto

![csgoguns example image](/assets/csgoguns_example1.png)

### `g/csgomaps <user>`

Fetches map stats from a player. Valid items for `user` is the Steam ID (string of numbers) or your steam profile link name (https://steamcommunity.com/id/**yourlinkname**/).

![csgomaps example image](/assets/csgomaps_example1.png)

### `g/csgorecoil <gun> [type]`

Displays a gif of the weapon recoil. Valid items for `gun` is any CS:GO weapon's name. `type` is an optional argument that defines the gif to be either the recoil pattern or how you control it.

![csgorecoil example image](/assets/csgorecoil_example1.png)&nbsp;&nbsp;&nbsp;&nbsp;![csgorecoil example image2](/assets/csgorecoil_example_control.png)
