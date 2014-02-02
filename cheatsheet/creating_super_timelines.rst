Creating Super Timelines
------------------------
1. Step 1 – Find Partition Starting Sector

  ``mmls image.dd – calculate offset ##### (sector *512)``

2. Step 2 – Mount image for processing

  ``mount -o ro, noexec,show_sys_files,loop,offset=##### image.dd /mnt/windows_mount``

3. Step 3 – Create Comprehensive Timeline

  ``log2timeline -p -r -f winxp -z CST6CDT /mnt/windows_mount -w timeline.csv``

4. Step 4 – Filter Timeline

  ``l2t_process -b timeline.csv -k keywords.txt MM-DD-YYYY..MM-DD-YYYY``
