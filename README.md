## Introduction

Not much to see here. I program Minecraft-related tidbits, mostly in Java. Everything is open-source, because there's no reason otherwise. It is easier, nowadays, to create an open-source project than a closed-source one.

## Projects

### [UUIDVault](https://github.com/A248/UUIDVault)

Combines the fragmented UUID/name caches of MC plugins into a simple yet powerful aggregated API. Supports Bukkit, Bungee, Sponge, and Velocity. Requires Java 8+.

### [ArimAPI](https://github.com/Arim-Minecraft/ArimAPI)

Frameworks and utilities useful for nearly any MC plugin. Includes [UniversalRegistry](https://github.com/A248/UniversalRegistry). Requires Java 11+.

### [ArimBans](https://github.com/A248/ArimBans) - In Progress

The ultimate punitive solution for MC servers. Depends on ArimAPI. Supports Bukkit, Bungee, Sponge, and Velocity. Requires slf4j and Java 11+.

### Other

See [my github profile](https://github.com/A248).

## Developer Resources

### Maven Repository

All projects use this repository.

``` xml
<repository>
  <id>arim-repo</id>
  <url>https://dl.cloudsmith.io/public/anand-beh/arim-repo/maven/</url>
</repository>
```

See specific projects for `groupId`, `artifactId`, and `version` values. These fields are found in a project's `pom.xml`.

### Javadocs

The javadocs are attached to each artifact. Any IDE which recognises maven dependencies and can download attached sources/javadocs is able to fetch such docs.

## Justification of Free Software

*Put simply, software may be copied at no cost to the developer. It is the logical that it be sold at no price.*

The basic economics of software are as follows:

For any unit of software, there is a fixed initial cost to develop it, but beyond that, the marginal cost of production is zero. Thus software is said to be non-rival in consumption. No matter how many times it is copied or distributed, the cost remains only that which was originally input. The consumers of software, inasmuch as they download and use it, receive some positive benefit. Therefore it is efficient that no price be charged for software, since the net marginal benefit on each unit distributed is positive.

The good of man is to be in accordance with reason. With regards to sfotware, the maximisation of net benefit is most reasonable. Accordingly, it is proper that software be developed, then provided, simply.

## Licensing

All projects use the GNU GPL v3. The license file is usually located in the base directory of the project as LICENSE.txt and should be copied into binaries.
