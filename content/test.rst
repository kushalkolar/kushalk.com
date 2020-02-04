Backup with rsync
#################

:date: 2019-02-04 21:50
:tags: rsync, backup
:category: bah
:slug: rsync
:authors: Kushal Kolar
:summary: Learn how to use rsync to manage backups

``rsync`` is a great and easy tool to manage backups of directories on linux filesystems

**Basic Usage:**

.. code-block:: bash
        
        rsync -avP <src> <dst>

**Example:**

.. code-block:: shell

        rsync -avP /work/myself/my_precious_project /data/longterm/my_precious_project_backup

.. code-block:: python

        import numpy as np
        print("test some python stuff")

        l = [1, 2, 3, 4]
        
        d = {
        "bah":  232
        "b":    80
        }
        
        def bah(arg):
                a = np.array([1, 2, 3])
                return a



