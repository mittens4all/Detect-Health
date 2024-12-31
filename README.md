# Detect Health

This behavior pack uses scripts to detect the health of the player and convert it to a scoreboard objective.

## Installing the pack:

Add the Detect Health add-on to your behavior packs on your world. Behavior packs disable achievements, but editing the world with an NBT editor can re-enable achievements when uploading your world to a realm.

Re-enable achievements on either pc or mobile with the free NBT editor [Dovetail](https://github.com/Offroaders123/Dovetail)

## How to Use

You can display the scoreboard objective `detect_health` or target players using the scores as part of the target selector arguments:
```js
execute as @a[scores={detect_health=1}] at @s run <your-command-here>
```
## Author

- [@mittens4all](https://www.github.com/mittens4all)
- [Youtube](https://www.youtube.com/@mittens4all)

## Gratitudes

- [FatalConfuzion]
- [Bedrock Add-Ons Discord]((https://discord.gg/46JUdQb))

```js
       _                              _     _       _ _  
      (_)  _     _                   | |   (_)     | | | 
 ____  _ _| |_ _| |_ _____ ____   ___| |_____ _____| | | 
|    \| (_   _|_   _) ___ |  _ \ /___)_____  (____ | | | 
| | | | | | |_  | |_| ____| | | |___ |     | / ___ | | | 
|_|_|_|_|  \__)  \__)_____)_| |_(___/      |_\_____|\_)_)
                                                         
```