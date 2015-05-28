# Kodi's add-on related CEF parts

The folder contains all for Google Chromium Embedded needed parts which are complete required for the add-on.
Normally are own already created binaries from web used to give it as lib and to create add-on with them, this are different
from the normal ones to match Kodi's directory style and few changes on CEF are required.

Here is a small reworked version of the [automate-git.py script](https://bitbucket.org/chromiumembedded/cef/raw/master/tools/automate/automate-git.py) included which enable the Kodi related changes in the
source code of CEF. Also contains this folder the needed patch for it.

-------------
### License of original
- Copyright (c) 2008-2014 Marshall A. Greenblatt. Portions Copyright (c)
- 2006-2009 Google Inc. All rights reserved.
[New BSD License](https://github.com/AlwinEsch/web.KODIChromiumBrowser/blob/master/CEFParts/LICENSE-Chromium.txt)