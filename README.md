<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>RunQueue Monitor Plugin</title>
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
                <h1>RunQueue Monitor Plugin</h1>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
    </p>
    <p>
This plugin retrieves the size of the Run Queue from the specified host(s).    </p>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-PluginDetails"  >
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
<a href="attachments_149554261_1_com.compuware.plugins.runqueuemonitor_1.0.2.jar">com.compuware.plugins.runqueuemonitor_1.0.2.jar</a>    </p>
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
Dec 19, 2013. v1.0.2 - Initial Release    </p>
    <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-ProvidedMeasures"  >
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
QueueSize    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Integer value representing the runqueue size at the moment of execution of the plugin    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-Screenshotofthemeasuresscreen"  >
        <h2>Screenshot of the measures screen</h2>
    <p>
            <img src="images_community/download/attachments/149456522/2013-12-19_18_21_20_+00001.png" alt="images_community/download/attachments/149456522/2013-12-19_18_21_20_+00001.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-Configuration"  >
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
Host    </p>
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
Username    </p>
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
Username to be used to authenticate into the specified host where the Runqueue query is to be performed.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Password    </p>
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
Password to be used to authenticate into the specified host where the RunQueue query is to be performed    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-ScreenshotoftheConfigurationpage"  >
        <h2>Screenshot of the Configuration page</h2>
    <p>
            <img src="images_community/download/attachments/149456522/2013-12-19_18_20_58_+00001.png" alt="images_community/download/attachments/149456522/2013-12-19_18_20_58_+00001.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-UsageExample"  >
        <h2>Usage Example</h2>
    <p>
This plugin can be useful for tracking the runqueue size as well as by using dynaTrace Alerting, be proactively notified when the RunQueue exceeds a desired threshold.  Simply add this measure to a chart and observe the value over time.    </p>
    <p>
            <img src="images_community/download/attachments/149456522/2013-12-19_18_30_58_+00001.png" alt="images_community/download/attachments/149456522/2013-12-19_18_30_58_+00001.png" class="" />
                 <img src="images_community/download/attachments/149456522/2013-12-19_18_35_45_+00001.png" alt="images_community/download/attachments/149456522/2013-12-19_18_35_45_+00001.png" class="" />
            </p>
    </div>
    <div class="section-2"  id="149456522_RunQueueMonitorPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server via the dynaTrace Server Settings menu -&gt; Plugins -&gt; Install Plugin. For details how to do this please refer to the dynaTrace documentation:    </p>
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
