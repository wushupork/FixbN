FixbN
=====

Userscript for bannination.com

This script requires you to have Greasemonkey (for firefox) or Tampermonkey (for Chrome) installed in your browser.

Changes from Artificeren's version:

(1) Fixed auto-linkification for images with upper case letters in their extension (noted by bunnythor).
(2) Changed linkification to include target='_blank' for all links.
(3) Configurable strip club closing time.
(4) Added a configurable delay in the tagger (10 ms between tags, by default) to slow it down so it doesn't blast the server so badly on long tag lists.
(5) Timestamps now done with a different library. You can specify your own format, and choose between server time, local time, and UTC. If you choose "Local" you can also specify "Pretty" in which case timestamps will display as e.g. "a few minutes ago". (This library does not support dynamic rewriting of timestamps so they will no longer tick off seconds).

2015-01-29:  Merged Mass Tagger option written by Wushupork (https://github.com/wushupork/FixbN)
