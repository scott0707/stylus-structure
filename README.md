## Stylus Structure

Scott Kehr



###Folder Structure

Files with styl extension get compiled and compressed

Compressed files get moved into min folder

  * min folder lives at the root of parent module's stylesheet folder

  * Compressed file's path will match original files path relative to stylesheets folder

  * Compressed file's will have a css extension



###Imports

Instead of manifests we will use @import to concatenate Stylus files



###How to Convert

1. Create a file with a styl extension

2. Convert all files you need to concatenate into Stylus
  * CSS files will not be imported correctly

3. Import each stylus file you need in the order you need it

4. Stylus and imports can live within same file
  * Keep all imports at the top of the file for organizational purposes

5. Remove any manifest files you are no longer using



###Converting CSS to Stylus

1. Replace the css extension with a styl extension

2. Run grunt stylus and make sure it doesn't choke on anything
  * CSS is valid Stylus

3. Remove all css specific markup ({, }, :, ;)

4. Remove unneeded vender prefixes

5. Cleanup code by organizing blocks and creating mixins



###Stylus



###Nib



###Lib



###Vender
