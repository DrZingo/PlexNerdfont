# IBM Plex Mono NerdFont

IBM recently released their Plex fontface. I made a version that adds Powerline and Nerdfont's. 

| Variations  
| ---------- 
| ExtraLight
| Light
| Medium
| Regular
| Semibold
| Text
| Thin

## Intro

`/originals` - Unmodified IBMPlexMono font, from [here](https://github.com/IBM/plex)

`/nerdfont` - Patched fonts

## Installation

Install using your operating systems font management (ie. FontBook)


## Images

![code](https://imgur.com/mivxMXb.png)

![NERDTree](https://imgur.com/E5nRbNS.png)

![Powerline](https://imgur.com/b2Jd3cs.png)


## Development

### Setup

[Fontforge](https://fontforge.github.io/en-US/) (or install using your favorite package manager)

Python2/3 + configparser (install it using pip)

[nerdfont-patcher](https://github.com/sgolovine/nerdfont-patcher) (or [nerd-fonts](https://github.com/ryanoasis/nerd-fonts))


### Adding glyphs

```
fontforge -script font-patcher PATH_TO_FONT
--mono
--complete
--out OUTPUT_PATH
```
For windows fonts we add the `--windows` flag as well.

### Script 

WIP


## Issues/Contributing

If you find something broken or not working right feel free to submit an issue and/or pull request.


## Tools/Sources

[IBM Plex Font](https://github.com/IBM/plex)

[Nerdfonts](https://github.com/ryanoasis/nerd-fonts)