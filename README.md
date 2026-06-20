# MultiLoader Template

This project is a fork of [jaredlll08/MultiLoader-Template](https://github.com/jaredlll08/MultiLoader-Template). For more information about the original architecture, see the upstream repository.

It provides a Gradle project template for building the same Minecraft mod for Fabric and NeoForge while keeping most source code and resources in a shared `common` module.

This branch targets Minecraft 1.21.1 and Java 21.

## What is different in this fork?

- Backports the newer upstream template structure from Minecraft 26.2 to 1.21.1.
- Update Fabric-Loom and ModDevGradle and Gradle to lastest version
- Apply ParchmentMC mapping
- Add Modrinth and CurseForge maven repositories
- Add Mod Menu for Fabric and JEI for both mod loader by default

