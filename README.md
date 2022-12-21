# keep2joplin

google keep 2 joplin

Convert google keep to joplin file.

Support to import title, content, hyperlink(Annotations), attachments, creation time, modification time, etc.

How to use:

* Visit https://takeout.google.com to export google keep data
* Unzip files like `takeout-**********-***.zip`
* execute `keep2joplin.exe -src=C:\Users\***\Downloads\takeout-20220804T040209Z-002\Takeout` or `keep2joplin  -src=/home/***Downloadstakeout-20220804T040209Z-002akeout`
* keep2joplin will create a `keep` directory to hold the converted files
*Open joplin, click File->Import->Import MD - markdown + (directory), select `keep` directory

