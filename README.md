## Projects

| Project | Category | Description                                                                 | Dependencies |
|-------------------|-----|------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| [UniversalRegistry](https://github.com/A248/) | `java` | A common framework for events, resource registrations, and multi-threaded utilities.  | n/a |
| [NeoTime](https://github.com/A248/NeoTime/)           | `java` | A base-ten system of time measurement. It is a superior alternative to the traditional 365-day year.                                                 | n/a |
| [ArimAPI](https://github.com/A248/ArimAPI)           | `java`/`minecraft` | An efficient, easy-to-use minecraft plugin library and framework.                                                                                    | UniversalRegistry |
| [ArimBans](https://github.com/A248/ArimBans)          | `java`/`minecraft` | The ultimate punitive solution for Spigot servers and BungeeCord networks, seeking to maximise efficiency through near-total asynchronous operation. | ArimAPI, UniversalRegistry |
| [NPCSk](https://github.com/A248/NPCSk)             | `java`/`minecraft`/`skript` | Solid Skript NPC handling using JitseB's NPCLib and bensku's Skript.                                                                                 | UniversalRegistry, [Skript](https://github.com/SkriptLang/Skript/), [NPCLib](https://github.com/JitseB/NPCLib/) |
| [EulerEstimator](https://github.com/A248/EulerEstimator)    | `java` | Approximates the value of some y given a differential equation relating dy/dx, y, and x using Euler's approximative approach.                        | n/a |

## Maven Repository

All projects use this repository. See a project's homepage for `groupId`, `artifactId`, and `version` values.

``` xml
<repository>
  <id>arim-repo</id>
  <url>https://www.arim.space/repo/repository/maven-snapshots/</url>
</repository>
```

## Justification of Free Software

*Put simply, software may be copied at no cost to the developer. It is the logical that it be sold at no price.*

The basic economics of software are as follows:

For any unit of software, there is a fixed initial cost to develop it, but beyond that, the marginal cost of production is zero. Thus software is said to be non-rival in consumption. No matter how many times it is copied or distributed, the cost remains only that which was originally input. The consumers of software, inasmuch as they download and use it, receive some positive benefit. Therefore it is efficient that no price be charged for software, since the net marginal benefit on each unit distributed is positive.

The good of man is to be in accordance with reason. Where costs and benefits, the substance of economics, are concerned, efficiency is most reasonable. Accordingly, it is proper that software be developed, then provided, simply.

## Licensing

All projects use the GNU GPL v3. The license file is usually located in the base directory of the project as LICENSE.txt and should be copied into binaries.
