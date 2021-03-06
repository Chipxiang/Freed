# Freed

Author: Jianxiang Li, Hao Wang

Design: A script-based escape room game that player gets clues and keys via text descriptions and sounds in the room to escape.

Text Drawing:

The text to display and its color/size -->  Use harfbuzz API to create buffer to hold text and shape the text contents into glyphs -->
--> Compute positions of each char based on its glyph information --> Draw 2 triangles to show 1 texture which corresponds to 1 char from the text. 

Text is loaded during initialization of the game. It is rendered at runtime.



Screen Shot:

![Screen Shot](screenshot.png)

How To Play:

Use &#8593; and &#8595; keys to select your choice.\
Press space to confirm.\
Sound is important so please don't mute.

**HINT**: If you get stuck, all of our scripts are in `dist/texts` :)
 
Sources:

Really Free Font: https://www.fontspace.com/really-font-f45186 \
Walking: https://freesound.org/people/13FPanska_Stranska_Michaela/sounds/378398/ \
Keyboard: https://freesound.org/people/Trollarch2/sounds/331656/ \
Open box: https://freesound.org/people/tommy_mooney/sounds/386696/ \
Make bed: https://freesound.org/people/Iamgiorgio/sounds/371308/ \
Flip book: https://freesound.org/people/Tats14/sounds/408786/ \
Lock open: https://freesound.org/people/fastson/sounds/399120/ \
Read disk: https://freesound.org/people/Anika11/sounds/325686/ \
Wake up: https://freesound.org/people/vanishedillusion/sounds/500618/ \
Drawer: https://freesound.org/people/cMilan/sounds/426769/ \
BGM: https://freepd.com/music/Halloween%20Theme%201.mp3 \
Game end: https://freepd.com/music/City%20Sunshine.mp3 \
Shader Program modified from: https://github.com/GenBrg/MarryPrincess/blob/master/Texture2DProgram.cpp#L81 \
Drawing text with OpenGL, Harfbuzz, FreeType: https://learnopengl.com/In-Practice/Text-Rendering, https://github.com/GenBrg/MarryPrincess/blob/master/DrawFont.cpp \


This game was built with [NEST](NEST.md).
