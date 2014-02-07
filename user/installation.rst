Installation
============

We tried to make the installation (and upgrade) of the SIFT workstation as simple as possible, so we create the SIFT Bootstrap project, which is a shell script that can be downloaded and executed to convert your Ubuntu installation into a SIFT workstation.

Check the project out at https://github.com/sans-dfir/sift-bootstrap


Quickstart
----------
Using `wget` to install the latest

.. code-block:: html

    wget -O - https://raw.github.com/sans-dfir/sift-bootstrap/master/bootstrap.sh | sudo sh -s -- -i
    

Using `curl` to install the latest

.. code-block:: html

    curl -L https://raw.github.com/sans-dfir/sift-bootstrap/master/bootstrap.sh | sudo sh -s -- -i


Using `wget` to install the latest, configure and use apply the SIFT theme

.. code-block:: html

    wget -O - https://raw.github.com/sans-dfir/sift-bootstrap/master/bootstrap.sh | sudo sh -s -- -i -s -y