# APFS_010
This is an [010 Editor](http://sweetscape.com/010editor/) template for APFS. It is a port of apfs.ksy with some additions/modifications. The original is located here:
https://github.com/cugu/apfs.ksy

## License
MIT

## Usage
To use the template, simply load your raw disk image into 010. Then edit the template to set the Apfs_Offset variable to the byte offset of wherever your APFS partition starts. If the image is encrypted, you will still be able to navigate to the encrypted blocks, but not read any further. On encrypted volumes, you will not be able to get to file listings or file contents as the disk blocks for data and metadata are encrypted!

## Contribute
Feel free to submit changes (pull requests) here and to the original [apfs.ksy](https://github.com/cugu/apfs.ksy) project.
