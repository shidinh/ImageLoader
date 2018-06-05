# ImageLoader
Basic HTML web-resource which can be used to upload and render images on the Dynamics 365 CE forms.

To use this on the Dynamics 365 forms, the following steps need to be done:
1. Create a new HTML web-resource using the 'ImageLoader.html' file.
2. Create a new MLT attribute on the entity where you want to show the Image.
3. Update the HTML web-resource created in step 1 and update the 'multiLineAttribute' variable on line 24.
4. Open the desired form of the entity. Place the MLT attribute created in step 2 and the HTML web-resource created in step 1 on the form 
(Fomratting: 20 lines or as desired).
Ensure that the MLT attribute is hidden by default and that the HMTL web-resource has show borders = NO.
5. Save and publish all changes.
6. Image loader should be now seen on the modified form!

Tested in Chrome 66.0.3359.181, Firefox 60.0.1, IE 11.
