Overview
========

This repository contains versions of `playerglobal.swc` which are used to target each major release of Adobe Flash Player by dynamically linking against the relevant swc when compiling with mxmlc or Falcon.

Usage
=====

`git clone git://github.com/nexussays/playerglobal.git` to `<flex_sdk_root>/frameworks/libs/player`

For example:
```
nexus@NEXUS-TABLET C:\develop\sdk\flex_sdk_4.6.0.23201\frameworks\libs
$ rmdir player /s /q

nexus@NEXUS-TABLET C:\develop\sdk\flex_sdk_4.6.0.23201\frameworks\libs
$ git clone git://github.com/nexussays/playerglobal.git player
```

> See http://sourceforge.net/adobe/flexsdk or http://www.adobe.com/go/flex_sdk to obtain the Flex SDK

License Notice
==============

Mozilla Public License.

The contents these files are subject to the Mozilla Public License Version 1.1 (the "License"); you may not use these files except in compliance with the License. You may obtain a copy of the License here: http://www.mozilla.org/MPL/.

Software distributed under the License is distributed on an "AS IS" basis, WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License for the specific language governing rights and limitations under the License.

The Original Code consists of the files listed above.

The Initial Developer of the Original Code is Adobe Systems Incorporated.