# Mod Template

A reusable starting point for Minecraft Java 1.21.11 Fabric mods.

## What's included

- Gradle build setup (`build.gradle`, `settings.gradle`, `gradle.properties`)
- GitHub Actions workflow that builds the jar automatically (`.github/workflows/build.yml`)
- Mod Menu entry point and settings screen structure
- Mixin config and folder layout
- Icon folder for the Mod Menu icon

## How to use

1. Click **Use this template** on this repo, or copy the files.
2. Rename `modtemplate` to your mod's id in the package folders, file names, and contents.
3. Update `fabric.mod.json`, `gradle.properties`, and `settings.gradle` with your mod's details.
4. Add your code under `src/main/java`.
5. Commit your changes. The Build workflow will build the jar.
6. Download the `.jar` from the **Actions** tab, under **Artifacts**.

## Requirements

- Minecraft Java Edition 1.21.11
