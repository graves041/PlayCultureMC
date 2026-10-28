# PlayCultureMC

One Minecraft plugin for the PlayCulture games. Run one, two or all of them on the same server, with a single resource pack.

| Game | Status |
|------|--------|
| **SeekTag**: hide, hunt and spot numbered vests | Available |
| **Zombies**: survive, infect, extract | In development |
| **Pirate Gold**: trade, raid and plunder | Coming later |

## Website

Rules, setup guides, commands, permissions and downloads are all on the website:

**https://playculturemc.graves041.com**

- [Downloads](https://playculturemc.graves041.com/downloads): plugin jar and resource pack (Java and Bedrock)
- [Setup guide](https://playculturemc.graves041.com/guide)
- [SeekTag](https://playculturemc.graves041.com/seektag/) · [Zombies](https://playculturemc.graves041.com/zombies/) · [Pirate Gold](https://playculturemc.graves041.com/pirategold/)

## Requirements

- Paper or Purpur 1.21.11
- Java 21
- Optional: PlaceholderAPI, Floodgate and Geyser (for Bedrock players)

## Quick start

1. Download `PlayCultureMC-1.0.0.jar` and the resource pack from the website.
2. Put the jar in your server's `plugins` folder and start the server.
3. Host the resource pack and set it in `server.properties`, then follow the setup guide to create your first arena.

## Building from source

```
mvn -q -B package
```

The jar is written to `target/`.

## Credits

Inspired by [PlayCulture](https://www.playculture.com). This is a fan-made project and is not affiliated with PlayCulture.
