mmproxy
===
mmproxy is a middle-man proxy for mobile phones to surf the internet via implicit proxies automatically.

Architecture
---
+-----------------+  +-----------------------+  +-------------------+
|Your mobile phone|--|        mmproxy        |--|      Internet     |
|  (e.g. android) |--|on your wireless router|--|(e.g. facebook.com)|
+-----------------+  +-----------------------+  +-------------------+

Installation
---

Technology
---
  * erlang/OTP
  * iptables

Reference
---
  * mitmproxy - an SSL-capable man-in-the-middle proxy for HTTP. It provides a console interface that allows traffic flows to be inspected and edited on the fly. https://github.com/cortesi/mitmproxy

The GPL3 license
---
This project is published under GPL v3.

mmproxy - a middle-man proxy for mobile phones to surf the internet via implicit proxies automatically.

Copyright (C) 2012 Evan Liu (hmisty@gmail.com)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
