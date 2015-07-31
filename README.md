#Space 48 - Pdf WYSIWYG Upload

## Description
Very minimal module to allow for PDF files to be uploaded via the Magento admin WYSIWYG interface.

This was created as an example of how a simple modification can be made via a module instead of editing the core directly - this was for a particular feature that on the face of it is not necessarily easy to do (an xml change).

There are recomendations out there to do this type of modification by copying the core xml file in to the local code pool. This _will_ work, but it does mean that future upgrades are more challenging as the copied xml file may be missing new functionality from the upgrade.

It is a side point that uploading PDFs via the image might not be the best idea. But hopefully this helps someone.
