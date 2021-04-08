# BFBB HD Texture Pack

An HD Dolphin texture pack for SpongeBob SquarePants: Battle for Bikini Bottom, meant for use in Dolphin emulator.

This pack was originally just hosted as a Google Drive link, but I am now hosting it here to better track updates I plan to make in the future.

## Video Showcase

<https://www.youtube.com/watch?v=etDwHwIb_Dc>

## Installation

- Download this respository, either the latest repo files or the latest release
- Place the GQPE78 folder inside your `./Dolphin Emulator/Load/Textures` folder
- Enable the "Load Custom Textures" option in Dolphin
- For better performance, enable "Prefetch Custom Textures" as well

NOTE: This is only compatible with Dolphin 5+

## How it was made

- Used the Xbox version of the textures as a base, as they are not BC1/DXT1 compressed and some are higher resolution than GameCube
- Upscaled textures using a custom trained ESRGAN model, trained on high quality frames of SpongeBob episodes downscaled similarly to the textures and indexed/dithered with the same number of colors
- Upscaled textures were then manually touched up in Photoshop in order to fix certain issues
- Certain textures (sand, mostly) were remade manually as the upscaled results were not good
- Certain textures were recreated using official Nickelodeon SpongeBob assets gathered from the "SuperSponge" disk leak
- The textbox texture was yoinked from a video of Rehydrated gameplay before its release, and then modified to match the original's coloring.

## Discord

<https://discord.gg/KZ3tjV4>