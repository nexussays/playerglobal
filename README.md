Overview
========

This repository contains a version of `playerglobal.swc` (a code library containing the API to Adobe Flash Player) coresponding to every major release of Adobe Flash Player. You can target the version of your choice by dynamically linking against the relevant swc when compiling with mxmlc or asc2.0 (eg, `-target=11.5`, `-target=10.1`).

Usage
=====

Setup
-----

1. Open a terminal / command prompt and navigate to the root of your Flex SDK directory.
   
   ```bash
   cd <flex_sdk_directory>
   ```

2. Delete `frameworks/libs/player`.
   
   ```bash
   rmdir frameworks\libs\player /s /q # Windows
   sudo rm -rf frameworks/libs/player # Mac/Linux
   ```

3. Clone this repository to `frameworks/libs/player`.
   
   ```bash
   git clone git://github.com/nexussays/playerglobal.git frameworks/libs/player
   ```

> See http://sourceforge.net/adobe/flexsdk or http://www.adobe.com/go/flex_sdk to obtain the Flex SDK

Update
------

Simply `git pull` whenever a new version of Flash is released to get the new swc. Or run the `update.bat` file on Windows.

License Notice
==============

```
Mozilla Public License.

The contents these files are subject to the Mozilla Public License Version 1.1
(the "License");you may not use these files except in compliance with the
License. You may obtain a copy of the License here: http://www.mozilla.org/MPL/.

Software distributed under the License is distributed on an "AS IS" basis,
WITHOUT WARRANTY OF ANY KIND, either express or implied. See the License for the
specific language governing rights and limitations under the License.

The Original Code consists of the files listed above.

The Initial Developer of the Original Code is Adobe Systems Incorporated.
```
