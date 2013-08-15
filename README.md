ForgeMod
========

Maven parent POM for building mods with [Minecraft Forge](http://minecraftforge.net/) using [SpecialSourceMP](https://github.com/agaricusb/SpecialSourceMP).

Add to your parent pom.xml (for Minecraft 1.6.2):

      <parent>
        <groupId>net.md-5</groupId>
        <artifactId>ForgeMod</artifactId>
        <version>1.6.2-9.10.0-SNAPSHOT</version>
      </parent>

then run:

    mvn package

The mod will be compiled and reobfuscated in `target/`.

For more information see the wiki: https://github.com/agaricusb/ForgeMod/wiki

