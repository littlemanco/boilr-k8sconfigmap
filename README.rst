====================
k8sconfigmap
====================

Project Outline
----------------

Project Goals
'''''''''''''

Make it easy to deploy Kubernetes config maps

Similar Work
''''''''''''

None


Justification
'''''''''''''

Following conventions can get tiresome if it's not trivial


Summary
'''''''

============= ==============
License       Language
------------- --------------
MIT           en-AU [lang]_
============= ==============

Installation
-------------

.. Code:: bash

  $ boilr template download littlemanco/boilr-k8sconfigmap k8sconfigmap
  
Updates
-------

I update these templates regularly. If you need to fetch the newer version, try this:

.. Code:: bash

  $ boilr template download littlemanco/boilr-k8sconfigmap k8sconfigmap -f 

Usage
-----

Swap `foo` and `bar` for your own values.

.. Code:: bash

  $ mkdir foo
  $ cd foo
  $ git init
  $ git remote set-url origin git@github.com:foo/bar.git
  $ boilr template use k8sconfigmap .
  $ git add .
  $ git commit -m "Initial Commit"
  $ git push

Thanks
------

- The team behind boilr (https://github.com/tmrts/boilr)

Contributing
------------

Contributions are always welcome! Nothing is to small, and the best place to start is to open an issue.

References
-----------

.. [lang] Lingoes.net,. (2015). Language Code Table. Retrieved 4 June 2015, from http://www.lingoes.net/en/translator/langcode.htm
