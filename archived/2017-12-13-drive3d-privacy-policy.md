---
layout:      post
title:       Drive3D Privacy Policy
date:        2017-12-13
categories:  files
author:      Herman Bergwerf
---

Drive3D is an open-source web application that enables you to use WebGl to
view OBJ/MTL files that are stored on Google Drive. The source code of Drive3D
can be found at [github.com/bergwerf/drive3d](https://github.com/bergwerf/drive3d).
The appliation is published at [drive3d.hermanbergwerf.com](http://drive3d.hermanbergwerf.com).

Drive3D uses OAuth in order to authenticate with Google Drive. This access is
used by the app to:

- Read OBJ and MTL files from your Google Drive for visualization
- List all OBJ files in your Google Drive account when you visit the application
- Search for an MTL file with the same name when you load an OBJ file in order
  to attach material settings

All data traffic happens on the client side (in the web browser). The entire
application is served statically by GitHub. The information obtained via the
Google Drive API is not shared with third parties.

Note that this application is made available under the terms of the MIT license.
If you find any issues or inconsistencies with regard to privacy, please open an
issue on GitHub at [github.com/bergwerf/drive3d/issues](https://github.com/bergwerf/drive3d/issues).
