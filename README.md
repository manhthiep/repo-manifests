repo-manifests
==============

Manifests for repo tool, also works with gittig

* Using **repo**:
  <pre>
  repo init -u https://github.com/manhthiep/repo-manifests.git -m MANIFEST_FILE
  repo sync
  </pre>
  
* Using **gittig**
  * Clone
    <pre>
    git clone https://github.com/manhthiep/repo-manifests.git
    gittig clone [--mirror] --manifest=repo-manifests/MANIFEST_FILE
    </pre>
  * Sync
    <pre>
    gittig sync [--mirror] [--manifest=repo-manifests/MANIFEST_FILE]
    </pre>
