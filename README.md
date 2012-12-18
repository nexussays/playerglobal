Overview
========

This repository contains versions of `playerglobal.swc` which are used to target each major release of Adobe Flash Player by dynamically linking against the relevant swc when compiling with mxmlc or Falcon.

Usage
=====

Clone this repository to `frameworks/libs/player` in your Flex SDK directory. You can then simply `git pull` whenever a new version of Flash is released to get the new swc.

eg, Windows:
```
cd C:\develop\sdk\flex_sdk_4.6.0.23201\frameworks\libs
rmdir player /s /q
git clone git://github.com/nexussays/playerglobal.git player
```
eg, Mac/Linux:
```bash
cd /opt/adobe/flex_sdk_4.6/frameworks/libs
sudo rm -rf player
sudo git clone git://github.com/nexussays/playerglobal.git player
```

> See http://sourceforge.net/adobe/flexsdk or http://www.adobe.com/go/flex_sdk to obtain the Flex SDK

License Notice
==============

Mozilla Public License.

The contents these files are subject to the Mozilla Public License Version 1.1 (the "License"); you may not use these files except in compliance with the License. You may obtain a copy of the License here: http://www.mozilla.org/MPL/.

Software distributed under the License is distributed on an "AS IS" basis, WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License for the specific language governing rights and limitations under the License.

The Original Code consists of the files listed above.

The Initial Developer of the Original Code is Adobe Systems Incorporated.
