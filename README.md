# vQmod XML Generator v3.2.1

* Generate XML files for use with vQmod versions 2.3.0 or greater
* Built-in File Manager and Log Viewer

**Pre-Requisite**

vQmod version 2.3.0 is required for this package

For further information on vQmod and to download it, please visit http://www.vqmod.com/

**author** Simon Powers - UK Site Buidler Ltd <info@uksitebuilder.net> - http://www.opencart-extensions.co.uk/

**copyright** Copyright (c) 2013, UK Site Builder Ltd

**version** $Id: README.md, v3.2.1 2013-02-05 22:30:00 sp Exp $

**license** http://creativecommons.org/licenses/by-sa/3.0/ Creative Commons Attribution-ShareAlike 3.0 Unported License


**Installation & Defaults**

1. Upload or upload and rename the 'vqgen' directory in this archive to your site root.
2. **IMPORTANT** Password protect the directory using htaccess/htpassword

If not putting the folder on the same level as the vqmod directory, edit the vqgen/index.php and change the relative paths for the set of 4 defines.


**Known Issues**

* Fails to read vqmod xml files that contain html comments which are outside of CDATA tags.


**Future Would Likes**

Generate a manual installation text or html file from the vqmod with easy to follow instructions
