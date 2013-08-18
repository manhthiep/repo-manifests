repo-manifests
==============

Manifests for repo tool, also works with pygit.py

* With repo:
  <pre>
  repo init -u https://github.com/manhthiep/repo-manifests.git -m <MANIFEST_FILE>
  repo sync
  </pre>
  
* With pygit.py
  <pre>
  git clone https://github.com/manhthiep/repo-manifests.git
  pygit.py clone [--mirror] --manifest=repo-manifests/<MANIFEST_FILE>
  pygit.py sync [[--mirror] --manifest=repo-manifests/<MANIFEST_FILE>]
  </pre>
