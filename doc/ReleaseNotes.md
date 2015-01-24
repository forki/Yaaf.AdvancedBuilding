﻿### 0.1.4

 * `releaseDir` Configuration is no longer required.
 * BREAKING: You can/must specify `outNugetDir` after updating!
 * fix some broken links in scaffold files.
 * add missing generateDocs.fsx scaffold file.
 * fix reference templates ending up in the wrong folder.
 * add chmod +x to default build.sh (because we can't add that to the nuget package)

 ### 0.1.3

 * add build.fsx as well.
 * fixed some problems with use_nuget=false.
 * added some files to the nuget package starting with a dot (nuget removed them previously).

### 0.1.2

 * a CONTRIBUTION.md file is now assumed in project dir (instead of doc/Contributing.md)
 * we assume a LICENSE.md now
 * added some scaffolding files to the nuget package
 * NuGet is now build on ./build All (as test on CI and to allow users to use them internally, its pretty fast anyway)

### 0.1.1

 * Fix invalid backward slash on linux.
 * Don't ask for task and branch push (use "git flow" and push manually!)


### 0.1.0

 * Initial release