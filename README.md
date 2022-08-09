## CS_Store
*Forked from https://github.com/tobyshooters/CS_Store*

An infinite canvas for your filesystem. 

### Some design decisions
1. All canvas state is stored in `.CS_Store` files. To send a canvas to
   someone, simply zip the directory and email it over.
2. Human-readable format for `.CS_Store` which can be manually edited with any
   text editor.
3. Size-as-context: When an element is added to the canvas, it's a fixed size
   in pixel width. To add a small comment, zoom-in to the context it concerns.
4. Audio as region: Sound files are played when visible in the canvas. Drop a
   file in to function as a soundtrack for a region of space.
5. Export to an .html with image files in a zip.

### Installation
1. Make sure you have the packages in `requirements.txt` installed
2. Add `display` to your path or move it to a bin in your path, or run `install.sh`.
3. Run `display`!

NOTE: At the moment, the `display` will assume this repository is located at `~/usr/repos/CS_Store`. Edit `display` to change this.

### To Do:
1. Watch for changes to the `.CS_Store` for live updates from text editor
2. Store text as `.txt` files, rather than in `.CS_Store` directly
3. Export button to generate `.zip`
4. Fix jittering on zoom-in on Safari
