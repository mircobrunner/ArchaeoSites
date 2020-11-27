# ArcheoSites360

How to install Landscapes
https://stellarium.org/landscapes.html


After you have downloaded the .zip file for a landscape from this page, you need to install it in Stellarium.
automatic

If you have Stellarium 0.10.6 or later version, you can use the 'Add/remove landscapes' feature to install landscapes automatically:

Open the 'Sky and viewing options' window by clicking on the appropriate button in the left button bar (or press the F4 key).
The 'Add/remove landscapes' button is at the bottom of the 'Landscape' tab.
When you press it, the 'Add/remove landscapes' window will appear. It allows you to install .zip files containing landscapes. It also lists the user-installed landscapes and allows you to remove them.

Note that while this makes installing landscapes easier, it may also cause you to overlook what else is included in the ZIP archive. Landscape packages created without this feature in mind may contain other files, such as alternative textures in different sizes.
manual

If you are using an earlier version of Stellarium, you can follow this procedure to install a landscape package:

Browse to your User Data Directory, which varies according to your operating system.
Create a sub-directory called landscapes in your user directory (if it doesn't exist).
Unzip the landscape .zip file in the landscapes directory (if it's done right, a sub-directory should be created for each landscape).

contributions

Please feel free to contribute your own custom landscapes here. Make thumbnails 200x114 pixels to fit with the rest of the page. Please include a location section in your landscape.ini file with the longitude, latitude, altitude and planet for the location of the landscape (see one of the pre-existing landscapes for an example).

To find out more about how to create a landscape, see the Stellarium User Guide, and examine existing landscapes. If you are having problems, posting to the forums is a good way to get some advice.
important note on image dimensions

IMPORTANT: Make sure all textures have dimensions which are integer powers of 2, i.e. 256, 512, 1024, 2048, 4096, 8192, 16384, ... e.g. 4096 by 1024, 2048 by 2048 and so on.

This is a limitation of OpenGL. Some video hardware will work OK with images with different image dimensions, but many will not display properly, suffer vastly reduced frame rates, and even crash the computer.

Please make sure all contributed landscapes conform to these requirements, or your link may be removed.

Be aware that many people's video hardware cannot handle very large textures. This is hardware and driver dependent. A typical maximum image size is 2048x2048 or 4096x4096.
package contents

Please package your landscape in a .zip file with all files inside a directory in the .zip file. This should be unique to your landscape, and it would be nice if it was all lower-case with no spaces.

You should also include a readme.txt file which describes the landscape and specifies any usage restrictions or licensing terms for the images used in the landscape.
licensing

Before you distribute images as part of a Stellarium landscape, please ensure you are legally entitled to - you must be the copyright holder for the images, or be able to distribute them for use with Stellarium under the terms of some agreement with the copyright holder (e.g. Creative Commons licensed images found on the web).

It is important to explicitly state what use may be made of images for your landscape. This should be done in the readme.txt file inside the .zip file.

We recommend an open source license compatible with Stellarium itself (i.e. the GNU GPL), or one of the Creative Commons licenses.
file encoding

The landscape.ini and readme.txt files should be UTF-8 encoded text or plain ASCII. It's probably a good idea to adopt the Windows line ending encoding, (i.e. CR LF). Both Windows and *nix style line ending encoding should work OK in Stellarium, but Windows users will have an ugly time reading the readme.txt if it uses *nix-style newlines.
need hosting?

If you have a landscape you would like to share but have no web-space to put it, email to any Stellarium developers and we'll put it on our site.
