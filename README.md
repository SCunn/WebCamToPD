# WebCamToPD
Processing sketch that enables webcam manipulation:

This is a Processing sketch I was working on where I was exploring how to track motion through the compuers webcam as a means of control for a Pure Data patch.  The Processing sketch works by taking a second screenshot and canceling out the colours then returns the  average distance  between two colours when movement is detected.  the sketch also uses the oscp5 library to send messages to netreceive in Pure Data, but I had an issue with creating packed messages for Pure Data to unpack.


