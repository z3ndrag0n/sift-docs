Mounting DD Images
------------------
.. code-block:: html

    mount -t fstype [options] image mountpoint

image can be a disk partition or dd image file

Useful Options

+---------------------------+-------------------------+
| Option                    | Description             |
+===========================+=========================+
| ro                        |  mount as read only     |
+---------------------------+-------------------------+
| loop                      |  mount on a loop device |
+---------------------------+-------------------------+
| noexec                    |  do not execute files   |
+---------------------------+-------------------------+
| offset=<BYTES>            | offset                  |
+---------------------------+-------------------------+
| show_sys_files            | system files            |
+---------------------------+-------------------------+
| streams_interface=windows | streams                 |
+---------------------------+-------------------------+