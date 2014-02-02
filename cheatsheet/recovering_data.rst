Recovering Data
---------------

Create unallocated Image (deleted data) using blkls
``blkls imagefile.dd > unallocated_imagefile.blkls``

Create Slack Image Using dls (for FAT and NTFS)
``blkls –s imagefile.dd > imagefile.slack``

Foremost Carves out files based on headers and footers
``foremost –o outputdir –c /path/to/foremost.conf data_file.img``

Sigfind - search for a binary value at a given offset (-o)
``sigfind <hexvalue> -o <offset> data_file.img``