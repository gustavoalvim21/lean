# For Mod Creators

For your mod to appear correctly in **Content Manager Lean**, it must include **two files in the root folder of the mod**.

> When **distributing your mod**, these two files must **already be included and properly configured** in the mod root folder.
>
> Lean can generate these files automatically for local use, but **for mod distribution**, they must be provided ready with the mod.

## Requirements

### 1. Preview

An image file in the mod root folder:

* `preview.png` or `preview.jpg`

This image will be used as the preview in Content Manager.

**Expected preview example:**

<img width="4000" height="2666" alt="bike_preview1" src="https://github.com/user-attachments/assets/f8c03d0d-5357-473e-805f-7d2353910292" />

### 2. Metadata

A file named:

```
metadata.json
```

Containing the bike metadata:

```json
{
  "manufacturer": "Aprilia",
  "model": "RS-GP",
  "year": "2025",
  "engine_type": "V4 four-stroke",
  "capacity": "1000 cc",
  "max. power": "280+ hp",
  "weight": "157 kg",
  "author": "Manu Mods",
  "version": "0.2b"
}
```

## Done

With this setup:

* The mod will be listed correctly
* The preview will be displayed
* The information will be shown in an organized way

Simple, fast, and straightforward.

<img width="1478" height="908" alt="Captura de tela 2025-12-16 154315" src="https://github.com/user-attachments/assets/8c532f1f-a80e-48dc-af0c-09a1311d7e1f" />

Thank you for contributing to the community.
