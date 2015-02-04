	# generateQRCode
	# Author: Ziga Makuc
	# QRCode generator by Jeromee Tienne	
	# Date: 4th of February, 2015
	# Version: 1.0
	# generateQRCode for Salesforce.com

1. Create Visualforce Page generateQRCode
2. Add Static Resource called "jQuery" and put file "jQuery-2.1.4.min.js" in it
3. Add Static Resource called "JavaScriptQRCode" and put file "jsqr.js" in it
4. Open page generateQRCode
  Option A: Add Id of the Account - it will show the name of the account
  Option B: Add parameters:
    txt [text that will be shown in QR Code]
    type [table/canvas]
    w [number, in px]
    h [number, in px]
    showName [null/1-shows name on top]
    
Comments: Currently not supported for PDF generation; will be release in next version
