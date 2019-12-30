# utf2dec.sh
Convert UTF8 characters to HTML decimal format

Ran into problems ages ago when polling Clash Royale API for clan statistics with bash, as the names in the game can contain basically any characters, including emojis and had to print them into a HTML-page.

This script converts characters to UTF8 codepoints and then to (HTML) decimal format.

Usage example:</br>
[user@some]$ bash utf2dec.sh sometext</br>
\&#115;\&#111;\&#109;\&#101;\&#116;\&#101;\&#120;\&#116;

