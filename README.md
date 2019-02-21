# shavit-style-doublejump
> Adds a custom double jump style to shavit's bhoptimer.

## Installation
1. Download the latest version from the [releases page](https://github.com/strafe/shavit-style-doublejump/releases/latest) and add it to your server.

1. Add a new style to `shavit-styles.cfg` with the `specialstring` key set to `doublejump`. Example:
```
"100"
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

ConVar|Default Value|Description
:-:|:-:|:-
`ss_doublejump_specialstring`|`doublejump`|Special string value to use in shavit-styles.cfg, only change this if the default collides with another plugin.
`ss_doublejump_max_double_jumps`|`1`|Maximum amount of jumps while mid-air after an initial jump.
`ss_doublejump_force`|`290.0`|The amount of vertical boost to apply to a player when double jumping. This value is used to scale the player's vertical velocity and immitate a mid-air jump.

## Demo
![Demo](demo.gif)
