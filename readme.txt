Memento Plugin for Mango Blog

Created by: Mark Aplet
Homepage: http://www.visual28.com/articles/memento

Memento is a super basic photo galley plugin that requires no database and no new tables to be created. It uses cfdirectory to get the contents of a memento folder and builds a gallery thumbnails automatically.


PLUGIN REQUIREMENTS

1. jQuery plugin (required to get shadowbox, lightbox or fancybox gallery effects)
2. Gallery Effect Plugins - Shadowbox, Lightbox, or Fancybox
3. ColdFusion 8 or higher

NOTE: ColdFusion 7 users can still get the old plugin here: http://www.visual28.com/assets/content/mango/Memento_CF7.zip However it will no longer be developed.



INSTALLATION

1. Copy the "Memento" folder into your BLOG-ROOT/components/plugins/user/ folder. Or use the auto install field from the plugin page of your mango admin. 

2. Activate the 'Memento Photo Gallery" plugin

3. Run through the initial configuration options setting your style of cropping if any and the size of your thumbnails. 

NOTE: If you wish to display image meta data be sure to use cfimage as the resize engine, and set the "Show image title" to yes. 



HOW TO USE MEMENTO

1. Click the "Files" button in the sidebar

2. Select the "memento" folder from the list

3. Create a new sub folder and give it a name e.g. "christmas2009" is a good one. This new folder is your Memento album.

4. Select your newly created folder and upload your large images to it.

5. Add the memento pseudo code to the page where you want the Memento gallery to go. 

6. The pseudo code looks like this: [memento:AlbumName] AlbumName is the name you gave your folder. e.g. "christmas2009"

7. Now go check your page and the photos will be created automatically.

NOTE: The first time Memento runs on your new album, it will automatically create the thumbnails for you. Depending on the number of images you added or how large they are it will take some time to process them. Be patient. If you are impatient or experiencing issues, try adding only a few images at a time and refreshing the page to build your gallery in smaller chunks.