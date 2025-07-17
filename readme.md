# Pinecil, ALH edition ![](./alh13.gif)


Manifest:

- Pinecil v1, ironOS v??
- Pinecil v2, ironOS v??
- custom boot logo.dfu https://ralim.github.io/IronOS/Logo/
- Pineflash v0.5.5 Windows [https://github.com/Spagett1/pineflash](https://github.com/Spagett1/pineflash/releases/tag/0.5.5) 
- clear case 


Resources: 

- Official firmware docu, IronOS https://ralim.github.io/IronOS/
- stock logos https://github.com/Ralim/IronOS-Meta/tree/main/Bootup%20Logos#logos-preview
- pineflash gui updater, supports pinecil v1 and v2; flash firmware OR boot logo https://github.com/Spagett1/pineflash
- v2 BLE webGUI (untested) https://joric.github.io/pinecil/
- v2 BLE webGUI (untested) https://github.com/builder555/PineSAM
- dismantle/repair/case mod 
  

Custom boot logo /animation (.dfu)
- create logo/anim (photoshop > layers > keyframes > export.gif) 
- install python
- run py script (gif > dfu)
- use PineFlash (or other updater) to flash logo.dfu
  
Current boot anim.gif.dfu
- 8 sec animation (~0.5s too long...)
- ![](./alh13.gif)


## To do??
- [ ] shorten boot anim by 0.5s or 1.0s (remove 1x 'blink' frameset?)
- [ ] display folder contents (gifs, pngs) in README
- [ ] update bootlogo instructions
- [ ] upload bootlogo python scripts

Auto-display all images in a folder?

- js node
  - https://stackoverflow.com/questions/66989447/i-want-to-display-images-in-a-github-repo-for-people-to-view >> github.com/nhoizey/nicolas-hoizey.com/blob/main/src/assets/logos/README.md
- jekyll?
  - https://gist.github.com/leabs/2542f92a168765b3faa1334c15da929f
  - https://www.reddit.com/r/Jekyll/comments/17eavo4/how_to_show_all_images_within_a_folder_directory/
- matplot
  - https://gist.github.com/sauravmishra1710/aeba76e0e0bb41230edf64338dc0dda7
