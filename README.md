**Vanish** allows players with permission to become completely invisible. Players, turrets, helicopters, NPCs, etc. will not be able to see, hear, or touch you!

**DON'T JUST SKIP OVER THIS!**

**In Vanish 0.5.0 permissions have been changed!**

**NOTE WHILE VANISHED:** You can hear players but they will be unable to hear you,. You are invisible to them and essentially do not exist to them. Even if they walk right through you they DO NOT know of your existence.

## Permissions
- `vanish.use` -- required to go invisible
- `vanish.damage.buildings` -- allows player to damage buildings
- `vanish.damage.animals` -- allows player to hurt animals while vanished
- `vanish.damage.players` -- allows player to hurt players while vanished
- `vanish.abilities.invulnerable` -- makes player invulnerable while vanished
- `vanish.abilities.teleport` -- allows player to teleport while vanished

## Chat/Console Command
- **vanish** -- Toggles player's invisibility on/off

## Configuration 
You can configure the settings in the Vanish.json file under the oxide/config directory.
```json
{
  "Play sound effect (true/false)": true,
  "Show visual indicator (true/false)": true,
  "Show visual overlay (true/false)": false,
  "Vanish timeout (seconds, 0 to disable)": 0,
  "Visible to admin (true/false)": false
}
```

## Localization
The default messages are in the Vanish.json file under the oxide/lang/en directory. To add support for another language, create a new language folder (ex. de for German) if not already created, copy the default language file to the new folder, and then customize the messages.
```json
{
  "CantDamageBuilds": "You can't damage buildings while vanished",
  "CantHurtAnimals": "You can't hurt animals while vanished",
  "CantHurtPlayers": "You can't hurt players while vanished",
  "CantUseTeleport": "You can't teleport while vanished",
  "CommandVanish": "vanish",
  "NotAllowed": "Sorry, you can't use '{0}' right now",
  "VanishDisabled": "You are no longer invisible!",
  "VanishEnabled": "You have vanished from sight...",
  "VanishTimedOut": "Vanish timeout reached!"
}
```

## Credits
- **Nogrod**, for all the help along the way. Cheers!
- **dcode**, for the awesome icon
