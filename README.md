## WebRTC Leak Prevent
#####Version 1.0.7 | January 21 2016

WebRTC Leak Prevent provides user control over WebRTC settings in Chromium that have no native GUI. The intended use of the extension is to prevent [WebRTC leaks](https://diafygi.github.io/webrtc-ips/).

The only required permissions are 'privacy' and 'storage'.

#####How it works

In **Chromium version 48+**, the extension provides user control over `webRTCIPHandlingPolicy`, defaulting to `default_public_interface_only`.

In older versions of Chromium, legacy options are supported. This includes `webRTCMultipleRoutesEnabled` for **Chromium version 42+**, and `webRTCNonProxiedUdpEnabled` for **Chromium version 47+**.

#####Download

[Chrome Web Store](https://chrome.google.com/webstore/detail/webrtc-leak-prevent/eiadekoaikejlgdbkbdfeijglgfdalml)

[Opera Addons](https://addons.opera.com/en/extensions/details/webrtc-leak-prevent/)

You may also run the extension unpacked via Developer mode. Just download or clone the repository.

---

#####Privacy

WebRTC Leak Prevent does not collect any user data. 

The extension is hosted entirely on GitHub, the Chrome Web Store, and Opera Addons. These services may collect user data.

#####License

Copyright 2016 rentamob

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
