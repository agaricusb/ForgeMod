ForgeMod
========

Maven parent POM for building mods with [Minecraft Forge](http://minecraftforge.net/) using [SpecialSourceMP](https://github.com/agaricusb/SpecialSourceMP).

Add to your parent pom.xml, for example:

      <parent>
        <groupId>net.md-5</groupId>
        <artifactId>ForgeMod</artifactId>
        <version>1.4.7-6.6.2</version>
      </parent>

then run:

    mvn initialize -P -built
    mvn package

The mod will be compiled and reobfuscated in `target/`.
