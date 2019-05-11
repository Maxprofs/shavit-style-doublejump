# shavit-style-doublejump
> 🔢 Double-jump style for shavit's bhoptimer.

## Installation
1. Download the latest version from the [releases page](https://github.com/strafe/shavit-style-doublejump/releases/latest).
1. Add a new style to `shavit-styles.cfg` with the `specialstring` key set to `doublejump`.
```
"NEW_STYLE_ID"
{
	"name"				"Double Jump"
	"shortname"			"DJ"
	"htmlcolor"			"FFA4D0"
	"command"			"dj; doublejump"
	"clantag"			"DJ"

	"unranked"			"1"
	"specialstring"			"doublejump"
}
```

## Configuration
The plugin can be configured in `cfg/sourcemod/plugin.shavit-style-doublejump.cfg`.

ConVar|Default|Description
:-:|:-:|:-
`ss_doublejump_specialstring`|`doublejump`|Special string value to use in shavit-styles.cfg, only change this if the default collides with another plugin.
`ss_doublejump_max_double_jumps`|`1`|Maximum amount of jumps while mid-air after an initial jump.
`ss_doublejump_force`|`290.0`|Amount of vertical boost to apply to a player when double jumping. This value is used to scale a player's vertical velocity and immitate a mid-air jump.

## Demo
![Demo](demo.gif)

## Credits
[Chanz](https://github.com/chanz) - [Infinite Jumping](https://github.com/chanz/infinite-jumping)

## License
[GPLv3](LICENSE)
