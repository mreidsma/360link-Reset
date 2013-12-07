# THIS SCRIPT HAS BEEN SUPERCEDED BY A NEW VERSION

The new version of this script is at [github.com/gvsulib/360link-reset](http://github.com/gvsulib/360link-reset)

-----

## README - 360Link-Reset

---

This tool was developed by Matthew Reidsma in Javascript to modify the SerialsSolutions 360Link link resolver.

INSTALLATION

Open 360link-reset.js in your favorite text editor and edit the path variable to the path and name to your 360Link CSS file. You can use the CSS file included in the script, but feel free to make it your own. If you want to replace the SerialsSolutions citation table with a semantic, HTML div that displays the citation in one line, change the value of the variable improveCitation to true. 

Now add two lines to your 360Link display. In the "footer" section of the Branding tab, add the following lines:

`<script type="text/javascript" src="http://code.jquery.com/jquery-latest.js"></script>`
`<script type="text/javascript" src="PATH/TO/360link-reset.js"></script>`

That's it! 

WHAT IT DOES:

360Link reset does a few things. First, it replaces the crummy, default (and custom) style sheets provided by SerialsSolutions with your own style sheet. Second, it removes all of the evil inline styles that have accumulated like cruft in the HTML of the link resolver. Then it removes the hated "target="_blank" from anchor elements because opening new windows should be up to users, not websites. (If you don't want that changed, just comment out line 71). Then the script replaces some unsemantic spans with proper headings and will rewrite that ridiculous citation table with more typical citation format in a single line.

More questions? Feel free to contact Matthew Reidsma on Twitter at @mreidsma or via email at reidsmam@gvsu.edu.

COPYRIGHT

This tool is copyright 2011 Grand Valley State University Libraries. 

This tool is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This tool is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this tool. If not, see <http://www.gnu.org/licenses/>.
