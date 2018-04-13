
COCOMO
------

A simple wrapper, essentially implementing the details written out
by David A. Wheeler and relying on his SLOCCount binary to do all
the heavy lifting. http://www.dwheeler.com/sloccount/sloccount.html

Dependencies
============


- python
- sloccount

On Mac `brew install sloccount`

On Debian `apt-get install sloccount`

On Redhat `yum install sloccount`

On Windows compile from source (see the gz file in this directory)

Installation
============


    git clone https://github.com/aira/cocomo.git
    cd cocomo
    pip install -e .
    cocomo  # to run it on the cocomo source code

If you've installed this updated version, all you have to do is:

    cd path/to/project
    cocomo

If you've accidentally installed from the "official" cocomo pypi repo by @chintal it want work.
If you're getting an `IOError` or `FileNotFoundError` you'll want to create a cocomo.yaml file in any project folder where you want to run this.
Then you can run cocomo with an argument to indicate a path to the folder you want to count:

    cocomo path/to/project/that/has/cocomo_yaml/file/


