# RaindanceMC/xpbottle

- **`xpbottle-module`** — Rain's Flexible Modules — XP Bottles: Experience, taken out of a player and put in a bottle. A plain glass bottle draws from the levels somebody is already carrying; a siphon bottle is held down to pull loose experience orbs off the ground as well. Nothing is rounded away — a bottle holds the exact number of points that went into it, and pours back exactly that many.
- **`xpbottle-standalone`** — Rain's XP Bottles: Rain's XP Bottles, as a plugin of its own. Nothing here but a build file and a descriptor: the xpbottle module and the standard wrapper are shaded together, and that is the whole plugin.

Part of [RaindanceMC](https://github.com/RaindanceMC); built on [RainsCore](https://github.com/RaindanceMC/RainsCore) and the shared parent in [framework](https://github.com/RaindanceMC/framework). Split out of `rains-flexible-modules` on 16.10.2026, history kept.

## Build

```
mvn install
```

Needs Java 25 and read access to `packages.tstieh.de` (server ids `packages-releases` / `packages-snapshots` in `~/.m2/settings.xml`).

## Plugins

- `xpbottle-standalone/target/RainsXPBottles-1.4.0.jar` — also published as `de.raindancer.modules:xpbottle-standalone:1.4.0`

## Versions

A module's version is a property in this repository's root `pom.xml`, a plugin's is `plugin.version` in its own pom. CI publishes every version that is not in the registry yet on the next push to master.
