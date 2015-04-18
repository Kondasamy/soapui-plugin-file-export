# SoapUI plugin - To export Request and Response to file/s#
SoapUI OS/ Pro plugin - Used for exporting Request and Response from Project, TestSuite, TestCase and TestStep level.


### **About the Plugin:**###
**SoapUI** – *“Export Request & Response Plugin”* is basically a Java Archive file (JAR), which has been coded to extend the capability of Core SoapUI functionalities. This plugin is basically compatible for/ from the version of SoapUI 4.5.0 till 5.1.2, no matter it is Open Source or Pro.

This plugin helps to export Raw Request and Raw Response of the SOAP/ REST/ HTTP Test Step, where the action can be performed for a single TestStep and for bulk export, the user could use action from TestCase/ TestSuite/ Project levels.

### How to install the Plugin? ###
The user needs to place the JAR file (soapui-plugin-file-export-1.0.0-plugin.jar), into the SoapUI Installation folder location %SoapUI Install Directory%\bin\plugins a shown below,

**Note:** The ‘plugins’ folder should be manually created if it doesn’t exist.
 
### How to Test the installation? ###
SoapUI needs to be restarted after installing the plugin. After SoapUI is opened, check the SoapUI Log for the traces of information stating the success of Plugin installation as below,

### How to use the Plugin? ###

1)	The user needs to right click any TestStep/ TestCase/ TestSuite/ Project and see the availability of a new option called Export Request and Response. This action has been added by the Plugin.

For Instance, if the user right clicks a TestSuite, the above action will be provided as below,

2)	After clicking the option, the plugin will loop and inspect through the SOAP/ REST/ HTTP teststeps and export to the Current User’s default folder location which will be published in the SoapUI log on successful attempts as shown in the below image,

3)	On successful completion, a popup will be displayed stating the completion as below,

4)	The user can navigate to the folder location stated in the SoapUI Log and could see the exported files,

Note: For the TestStep’s not ran or having null response, appropriate message will be logged in SoapUI Log.

### Future Enhancements: ###
This plugin fall through the point, if we are using the data driven concepts (usage of datasources). In future enhancements, this could be eradicated.





