## UILayouts
Showing examples of different layouts using the UI-Builder.

### Description:
This sample provides a collection of html pages showing different layouts. 
It focuses on layout only and therefore no further functionality is provided.

**Camera setup page**
Within pages\CameraSetup\CameraSetup.html a two column layout is shown with a 2D viewer on the left and a settings column on the right. 
It was necessary to add a few lines of CSS code. You can find these definitions in pages\CameraSetup\style.css

**Multi column layout page**
Within pages\MultiColumnLayout\multiColumnLayout.html a two column layout with equally sized columns is shown. To add more columns, click onto + next to column2 or drag and drop the ColumnLayout from the Elements into the according location.

**Viewer left, scrollable column right**
Within pages\ViewerLeftScrollableRight\viewerLeftScrollableRight.html a two column layout is shown with a 2D viewer on the left and a scrollable column on the right. It is necessary to insert a div element in the code view, which is not shown in the structure view. As this would be removed if the last element within the column is deleted, it is necessary to keep at least one element inside description-column, when working with the structure view.
Additionally, a few lines of CSS code are necessary, which can be found in pages\ViewerLeftScrollableRight\style.css.

### How To Run:
This sample can be run on the Emulator or on a device. 
After starting, the user interface can be seen at the DevicePage in AppStudio or by using a web browser.
AppStudio version >= 3.0.0 is required.

### More Information:
See tutorial UI-Builder layouting tutorial for more information

### Topics
System, User-Interface, Getting-Started, Sample, Layout, SICK-AppSpace
