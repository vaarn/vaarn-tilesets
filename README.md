# Vaarn Tilesets

This repository has two goals, the first is to provide a toolset for creating stylistically consistant overworld and dungeon maps for the TTRPG Vaults of Vaarn by Leo Hunt. The second is that the tiles and map templates within are a collaborative effort by anyone that finds value in this project.

Here is what is included so far:

- A tileset for hexmaps using ASCII gliphs
- An 8x8 pixel tileset for dungeon maps
- A Vaarn inspired color palette
- Example maps for editing
- Instructions on how to create maps
- Instructions on how you can contribute

# Tilesets

## Hex Tiles

The hex tiles in this repository were designed for use with hexkit and have a flat top. They were inspired by the [Regions of Vaarn](https://vaultsofvaarn.com/2020/07/14/regions-of-vaarn/) post on the Vaults of Vaarn blog.

<img src="images/vaarn-hex-tileset-example.png" alt="Hex Tile Exampe" style="width: 500px; height: auto;"/>

## Grid Tiles

The grid tiles are 8x8 pixel images and are designed to resemble roguelike games, and are not intended for a high level of realism. The power of these tilesets comes when combining the images with a tool like LDtk's rules editor to rapidly build maps with no design skills, and little effort.

<img src="images/vaarn-grid-tileset-example.png" alt="Grid Tile Exampe" style="width: 500px; height: auto;"/>

# How to Use This Repository?

I have spent a lot of time locating free tools to use, as well as keep things as simple as possible but by no means must you use any of the tools I recommend. In fact I encourage feedback to improvements to this document, tile submissions either by pull request, or direct communication are also welcome including tileset contributions that are compatable your mapping tool of choice.  

## Making new tiles

In this section I will quickly discuss the tools I am using for creating the tiles in this set.

### Libresprite

For the grid tiles, I have been using [libresprite](https://libresprite.github.io/#!/) a free and open source fork of [Aseprite](https://www.aseprite.org/). Either one of those tools will work, and are far superior to using a tool such as Gimp when working on 8x8 pixel tilesets. There are other pixel editors out there, so if you already have a favorite editor, I am sure it will work fine as well. I do not have a project file with layers for the tilesets, instead edit the `tilesets/grid/vaarn-8x8.png` tileset directly.

### Gimp

I have been using [GIMP](https://www.gimp.org/) to create the hex tiles, and I have all of the tile colors, borders, and glyphs in individual layers for easy combinations for export to png. This project file can be found in the `src` directory.

### Color Palette




# Contributing

Contributions to this project are welcome, and I will share as much as I can here to make that a smooth process if you choose to do so.
