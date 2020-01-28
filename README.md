# APFS_010
This is an [010 Editor](http://sweetscape.com/010editor/) template for APFS. It was initially a port of apfs.ksy with some additions/modifications. Since then, Apple released the official [specification] (https://developer.apple.com/support/downloads/Apple-File-System-Reference.pdf) and this has been updated to add most of the structures used in APFS. The original ksy file is located here:
https://github.com/cugu/apfs.ksy

## License
MIT

## Usage
To use the template, simply load your raw disk (or container) image into 010. Then run template. 

If the image is encrypted, you will still be able to navigate to the encrypted blocks, but not read any further. On encrypted volumes, you will not be able to get to file listings or file contents as the disk blocks for data and metadata are encrypted!

## Contribute
Feel free to submit changes (pull requests) here.
