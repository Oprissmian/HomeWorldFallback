

This config makes it so that if planet packs using Kopernicus' HomeWorldName option are uninstalled that the HomeWorldName is reset to Kerbin.

To make sure that the config works properly, the HomeWorldName for a planet pack should be implemented like this:

`@Kopernicus_config:BEFORE[ModName]`

`{`

`  @HomeWorldName = PlanetName`
  
`}`

Simply replace ModName with the name of your mod and PlanetName with the internal name of the body you want to apply the HomeWorldName to!

HomeWorldFallback is licensed under the MIT License

I encourage any planet modder using the HomeWorldName option to bundle this mod with their planet pack and make it a dependency ;-)
