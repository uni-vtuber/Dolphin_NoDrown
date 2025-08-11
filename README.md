# Dolphin No Drown

[日本語版はこちら](README_ja.md)

- simple Minecraft data pack that prevents your pet dolphins from suffocating.

## 📖 Description

Have you ever named a dolphin and worried about it getting stuck and suffocating? This data pack solves that problem! It grants the Water Breathing effect to any dolphin that has been given a name using a name tag, ensuring they can survive indefinitely underwater.

## ✨ Features

- **Prevents Suffocation:** Named dolphins will continuously receive the Water Breathing effect.
- **Lightweight:** A single command runs every tick, having a minimal impact on performance.
- **Server-Friendly:** Works on both single-player worlds and multiplayer servers.
- **No Visible Particles:** The effect is applied silently without any distracting potion particles.

## ⚠️ Limitations

- This data pack only prevents suffocation from being underwater. To respect vanilla game mechanics, it does **not** prevent dolphins from taking damage when they are beached on land.

## ⚙️ How It Works

This data pack uses a function that runs every game tick (20 times per second). This function identifies all dolphins that have been given a name and applies a brief, invisible Water Breathing effect to them. Because this check and effect application happens constantly, the named dolphins effectively have permanent water breathing, preventing them from drowning without creating any visual distractions like potion particles.

## 🛠️ Installation

1. Download the latest release of the data pack.
2. Open your Minecraft world's folder.
3. Navigate to the `datapacks` folder.
4. Place the downloaded `.zip` file into the `datapacks` folder.
5. If you are in the world, run the command `/reload`. If you are starting a new world, the data pack will be enabled automatically.

## 🗑️ Uninstall

To uninstall, simply remove the data pack file from the `datapacks` folder and run `/reload`.

This data pack does not require a special uninstall command. It only applies a temporary effect to dolphins and does not make any permanent changes to your world (such as creating scoreboards or tags). The effect will wear off naturally once the data pack is removed.

## 📝 Compatibility

This data pack is designed for **Minecraft: Java Edition 1.21.8 (`pack_format: 81`). It may work with other versions, but compatibility is not guaranteed.

---

Enjoy your immortal dolphins!
