# APFS_010
This is an [010 Editor](http://sweetscape.com/010editor/) template for APFS. It was initially a port of [apfs.ksy](https://github.com/cugu/apfs.ksy) with some additions/modifications. Since then, Apple released the official [specification](https://developer.apple.com/support/downloads/Apple-File-System-Reference.pdf), and this template has been accordingly updated to add most of the structures used in APFS. 


This template contains most of the changes included in the last spec update by Apple on 2020-06-22.

## License
MIT

## Usage
To use the template, simply load your raw disk (or container) image into 010. Then run template. 

If the image is encrypted, you will still be able to navigate to the encrypted blocks, but not read any further. On encrypted volumes, you will not be able to get to file listings or file contents as the disk blocks for data and metadata are encrypted!    
  

## Screenshots
![Template output after run](/Template_run.png "Template output")
  


![Template output showing inode structure](/Template_run_showing_inode.PNG "Template output showing inode structure")  

## Contribute
Feel free to submit changes (pull requests) here.
