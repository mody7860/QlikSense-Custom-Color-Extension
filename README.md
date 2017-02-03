# QlikSense-Custom-Color-Extension
Allows adding a legend to charts when using custom colors

INSTALLATION - 
Download the ap_widgets.zip to your server and import into QlikSense using the Extensions module in QMC.

After Import, the extension will be available for use.  Extension name - ap_widgets


EDIT EXTENSION - 
To edit or customize the extension, use the dev hub site.

USAGE - 
This extension allows users to add a legend to their chart when using custom colors.  When using custom colors the legend is not available. 
Note - this legend control uses a valuelist as a dimension.

1) To add the legend to a chart with custom colors, open the app in hub edit the chart and click on on Custom Objects from the menu on the left
2) After the legend has been added, click on the control in the UI and open the properties.
3) Under dimensions section in properties, click add dimension and specify the valueList dimension.  
   Example - ValueList('Red','Light Yellow','Light Green', 'Dark Green')
4) Under Appearance selection under the control's properties, expand the settings section.  
5) Under settings, you will see upto 4 colors which can be configured for your legend.  The colors you specify here will be directly linked to the dimensions you specified in your valuelist.
   
