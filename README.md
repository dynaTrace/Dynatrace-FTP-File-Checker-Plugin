<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>FTP File Checker Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>FTP File Checker Plugin</h1>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
    </p>
            <img src="images_community/download/attachments/148899445/icon.png" alt="images_community/download/attachments/148899445/icon.png" class="confluence-embedded-image" />
            <p>
This plugin checks the existence of a given file on an FTP Server and returns the result as a measure value of 0 or 1.    </p>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_149554230_1_com.dynatrace.FTPFileChecker_1.0.2.jar">FTPFileChecker v1.0.2</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Joe Hoffman    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
5.5+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Dec 16, 2013.  v1.0.1 - Initial Release    </p>
    <p>
Dec 18, 2013, v1.0.2 - Better error handling, compiled for v5.5    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-ProvidedMeasures"  >
        <h2>Provided Measures</h2>
    
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Measure    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
FileExists    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1; if the specified file is found on the FTP Server    </p>
    <p>
0; if the specified file is not found    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-Screenshotofthemeasuresscreen"  >
        <h2>Screenshot of the measures screen</h2>
    <p>
            <img src="images_community/download/attachments/148899445/Measures.png" alt="images_community/download/attachments/148899445/Measures.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-Configuration"  >
        <h2>Configuration</h2>
    <p>
The following properties need to be defined when setting up this monitor    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Property Name</strong>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Type</strong>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Default Value</strong>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Notes</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FTP Server Hostname    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
String    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
localhost    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
hostname or IP address    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FTP Server Port    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Long    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
21    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
changing this to 22 will not invoke SSL.  SSL is currently not supported by this plugin but could easily be added.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FTP Server Username    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
String    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FTP Server Password    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
String    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Directory    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
String    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
/    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
If left blank, the filename is checked in the default login directory.  To check on the file located in the <strong class=" ">foo</strong> directory, this field would contain <strong class=" ">/foo</strong>.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Filename    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
String    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
fileToCheck.txt    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-ScreenshotoftheConfigurationpage"  >
        <h2>Screenshot of the Configuration page</h2>
    <p>
            <img src="images_community/download/attachments/148899445/Settings_Example_set.png" alt="images_community/download/attachments/148899445/Settings_Example_set.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-UsageExample"  >
        <h2>Usage Example</h2>
    <p>
This plugin can be useful for detecting when a given file does or does not exist on a file system that is accessible by FTP.   This can be useful when a file existence or absence is used as a trigger for the beginning or completion of a batch job. The resulting measure can be plotted, displayed as a Traffic Light, and alerted upon via an action. Below is an example of showing the status of the file and showing an alert condition via a Traffic light when the file is not found.    </p>
    <p>
            <img src="images_community/download/attachments/148899445/Usage.png" alt="images_community/download/attachments/148899445/Usage.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="148899445_FTPFileCheckerPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the dynaTrace documentation:    </p>
    <p>
    </p>
    <p>
<a href="https://community/display/DOCDT55/Plugin+Management">Plugin Management</a>    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
