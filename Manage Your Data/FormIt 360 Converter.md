# FormIt Converter

---

Convert files from other applications to use within FormIt

The FormIt Converter is a Revit add-in that can convert files from other applications, such as SketchUp and Revit, to use within FormIt. It can be downloaded directly from the [FormIt website](http://formit360.autodesk.com/blog/formit-converter/).

## Convert RFA Files to FormIt files ![](Images/GUID-2CC7B106-9414-40FA-BD69-5884ACBA0834-low.png)

1. Choose Convert RFA to FormIt Content From the Ribbon menu
2. Browse to the local directory that contains RFA files you would like to convert to FormIt Content
3. Browse to the local directory where you would like the converted FormIt Content to be placed
4. Optionally check the Upload to A360 Drive Content Folder
5. Click OK and Revit will proceed to convert all RFA to FormIt Content \(.AXM files.\) Only the following categories are supported, all others will be ignored: Casework, Entourage, Furniture, Furniture Systems, Generic Models, Parking, Site, Specialty Equipment, Mass.

If you choose to upload the files to A360 drive, you will be prompted to log into Autodesk 360 \(if you are not already logged in Revit.\) The AXM files will be placed in the following folder in your A360 drive: /FormIt/Content. See [Content Library](../Content Libraries/README.md) to learn how to use this content within FormIt.

## Convert FormIt Sketch \(AXM\) Files to Revit Project ![](Images/GUID-45D30848-2C40-46BB-AC86-47372BB18DB1-low.png)

1. Download a FormIt sketch \(.axm file\) from your A360 drive
2. Start Revit 2015 and start a new project
3. From the add-in, choose Convert FormIt Sketch to RVT and browse to the .axm file you downloaded previously
4. The add-in will convert the geometry in the FormIt file and place it in the currently open RVT file 
   1. Sketched, extruded objects will become Mass families
   2. Grouped objects that are copied will be placed as instances of that same Mass family
   3. Groups that are assigned a specific category within FormIt will be placed as a family of that same category. You may manually replace these families with any other Revit family of that same category.
   4. Content that was converted with this add-in will be placed as a family of that same category. You may use the Reload function to replace these families with the proper RFA file \(see below.\)

## Convert SketchUp \(SKP\) Files to FormIt Sketch Files ![](Images/GUID-D6CF1FD4-6665-4748-872C-5D2855A84D1D-low.png)

1. Choose Convert SKP to FormIt Content From the Ribbon menu
2. Browse to the local directory that contains SKP files you would like to convert to FormIt Content
3. Browse to the local directory where you would like the converted FormIt Content to be placed
4. Optionally check the Upload to A360 Drive Content Folder
5. Click OK and Revit will proceed to convert all SKP to FormIt Content \(.AXM files.\)

If you choose to upload the files to A360 drive, you will be prompted to log into Autodesk 360 \(if you are not already logged in Revit.\) The AXM files will be placed in the following folder in your A360 drive: /FormIt/Content. See [Content Library](../Content Libraries/README.md) to learn how to use this content within FormIt.

## Replace FormIt Content with Revit Families ![](Images/GUID-B9500378-87F8-4458-858D-42A451164228-low.png)

1. Convert a FormIt sketch to a RVT file as outlined above
2. In the add-in, choose Reload Families
3. Browse to a local directory that contains RFA files that correspond to converted FormIt content
4. The add-in will proceed to replace any of the families with the correct families it finds in the selected directory



