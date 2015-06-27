# ios-build-utils
iOS Build Utility Scripts

# ipa Packager

Usage:

```
from ipa_packager import IpaPackager

ipa = IpaPackager("/path/to/MyApp.app","/output/path/MyApp.ipa")
ipa.package()
```

# Packager

Usage:

```
from utils.packager import Packager

p = Packager("package.zip")
p.add("/path/to/file")
p.add("/path/to/another/file","another/file")
p.package()
```

This Produces a zip file with

- package.zip
  - file
  - another/file
