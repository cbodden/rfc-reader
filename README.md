rfc-reader
====

This script is used to read RFC's, and search for RFC's by syntax.<br>
It has support for BCP, FYI, IEN, STD, & RFC.


Usage
----

&lt;pre&gt;&lt;code&gt;
Usage: rfc-editor &lt;name (-n)|read (-r)|search (-s)&gt; &lt;####&gt; &lt;bcp|fyi|ien|std|rfc&gt;

Usage examples:
  rfc-editor name 3334 rfc     # displays RFC #3334 name
    ex: 3334 Policy-Based Accounting. T. Zseby, S. Zander, C. Carle. October
             2002. (Format: TXT=103014 bytes) (Status: EXPERIMENTAL)

  rfc-editor search &lt;term&gt; rfc # Displays index of matches with RFC #'s
    ex: rfc-editor search transport rfc

        0905 ISO Transport Protocol specification ISO DP 8073. ISO. April
             1984. (Format: TXT=249214 bytes) (Obsoletes RFC0892) (Status:
             UNKNOWN)

        0939 Executive summary of the NRC report on transport protocols for
             Department of Defense data networks. National Research Council.
             February 1985. (Format: TXT=42345 bytes) (Status: UNKNOWN)

  rfc-editor read 38 fyi       # read fyi #38</code></pre>

Requirements
----

Less (http://www.greenwoodsoftware.com/less/)<br>
Wget (http://www.gnu.org/software/wget/)<br>
cURL (http://curl.haxx.se/)<br>
<br>and a terminal emulator of some sort, either:<br>
Xterm (http://invisible-island.net/xterm/)<br>
mrxvt (http://materm.sourceforge.net/)<br>
urxvt (http://software.schmorp.de/pkg/rxvt-unicode.html)<br>


License and Author
----

Author:: Cesar Bodden (cesar@pissedoffadmins.com)

Copyright:: 2013, Pissedoffadmins.com

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
