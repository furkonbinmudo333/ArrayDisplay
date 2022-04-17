# ArrayDisplay
#include &lt;Array.au3> $sString = 'why hello there' $sDelim = '^.*+|/?-[]{}()' $sReplaced = StringRegExpReplace($sString, ' ', $sDelim) MsgBox(0, '...', $sReplaced) _ArrayDisplay(StringSplit($sReplaced, $sDelim, 1)
