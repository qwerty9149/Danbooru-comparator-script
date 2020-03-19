# Danbooru-comparator-script

A script that my "friend" made me write for him to check on the number of smut to nonsmut artworks on danbooru. I don't want anything to do with this after this.

Modify the script as needed, it's really easy to.

For those who still don't understand it, just copy the elif to the next elif, change the number, the words that correspond to the new set you want, and a new text file containing all the names of the characters.

Everything you need is inside the Complete folder, along with some sample files.

The executing script is Main, modify this for more options. You will need to chmod +x Main, DanParallel and DanNoParallel. Txtfix is optional, but will also need to be chmod+x'd to use.

Requires curl, suggested to also get GNU Parallel for faster processing, and dos2unix to fix file errors from generating urls in Windows.
