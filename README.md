# klarasflat

## An experimental workflow for adding Tripo models to a Marble world...

<img width="1656" height="826" alt="vss" src="https://github.com/user-attachments/assets/5979dd8d-1a40-4dc8-a29e-f545c46d32e7" />

This is a Bohemian flat where an early 1980's Party Clown named Klara prepares her clients for intergalactic space voyages.  The space is a mix of mystery and magic.  This objective was to experiment with Marble to see how easily one could create a virtual set for ensuring consistency of character positioning when creating short film shots. 

I tried several iterations in Marble, including on the paid plan, but the one that I was happiest was the one I made for free, which also happened to be labeled as a "failed world!"  Ironically, it best captured the spirit of the set I am trying to achieve.  The loft is tall, airy, and atmospheric.  It has several stations for are creation as well as vintage stage lamps, 19th-century European art, near-Eastern arches, plants, wall chandeliers, and other flourishes.  Some parts of the world faze out prematurely, but this is part of the appeal, as it represents a liminal space between the world and the space beyond.

The game is to iteratively to improve the world by importing objects made using Tripo.  For a test case, I chose her workbench, which exhibited poor rendering quality in the Marble world.  I used SuperSplat Editor to bring in the Marble world and remove the old table.  Then I had ChatGPT create an app that would allow me to manually position the table with the edited world simply by feeding it the .zip export of the world from Marble and the .GLP worktable export from Tripo.

The link to that app, with the world loaded in it, should be [here](https://bohemian-loft-table.hollandaise-dh.chatgpt.site/)


## Getting Started:

  The zip file includes Klara's Marble loft, with exact Tripo table placement, and dependencies for offline use.

  On Ubuntu:

  1. Download and extract the file virtual-set-studio.zip (in the 'experiment' folder).
  2. Run:bash start.sh
  3. Load your Tripo model(s) into a Marble world and transform them appropriately for set dressing.

## Future Development:

  Build cape for auto-selecting clips of original world-building input image, for Tripo conversion.
  Secure API connection to send image to Tripo.
  Secure API connection to receive image back into Marble world for set dressing.
