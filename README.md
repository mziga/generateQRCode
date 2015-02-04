# generateQRCode for Salesforce.com	
	# generateQRCode for Salesforce.com
	# Author: Ziga Makuc
	# QRCode generator by Jeromee Tienne	
	# Date: 4th of February, 2015
	# Version: 1.0
	
# How to use it

1. Create Visualforce Page caled "generateQRCode"
2. Add Static Resource called "jQuery" and put file "jQuery-2.1.4.min.js" in it
3. Add Static Resource called "JavaScriptQRCode" and put file "jsqr.js" in it
4. Open page generateQRCode<br />
	Option A: Add Id of the Account - it will show the name of the account<br />
	Option B: Add parameters:<br />
		&nbsp;&nbsp;&nbsp;&nbsp;txt [text that will be shown in QR Code],<br />
		&nbsp;&nbsp;&nbsp;&nbsp;Type [table/canvas],<br />
		&nbsp;&nbsp;&nbsp;&nbsp;w [number, in px],<br />
		&nbsp;&nbsp;&nbsp;&nbsp;h [number, in px],<br />
		&nbsp;&nbsp;&nbsp;&nbsp;showName [null/1-shows name on top],<br />

Suggestions: You can incorporate QRCode in any VF Page (or site - be sure to select public availability for static resource) or use it in Account (or other object, if modified) as add-on to page layout.

Comments: PDF generation currently not supported; will be released in next version.
