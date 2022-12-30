![](images/ahlsbanner.png)
<h1 id='temp:C:abeefff3d3fa26f4e008d358ec9e'>A-HLS Create Task Workflow - Documentation </h1>

<i>A quick OmniScript that can be placed on various object record pages to quickly create tasks that are related to the current record. </i><br/>

<h2 id='temp:C:abec5f1daa027474fcc989543a65'>Overview</h2>

Tasks are a powerful tool for keeping on top of customer relationships and closing deals. By using task records, you and your teams can keep better track of your outstanding to-do’s. This helper is a process which allows users to create such tasks quickly from a record. <br/>

<h4 id='temp:C:abe88aaffa3eefb4aafb9afdc12a'><span style="color:#333333" textcolor="#333333">Use Case Scenario</span></h4>

<span style="color:#333333" textcolor="#333333">As a user of the application I want to be able top create a task quickly. </span><br/>

<hr style='width:100%'><h2 id='temp:C:abe51377823cac24410b06fff56c'><span style="color:#333333" textcolor="#333333">Business Value and Benefits</span></h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:abe81f2904d4b5e41728eff1a9d5'><li id='temp:C:abe26b92b3a5483445ebc51f40c1' class='' value='1'>Reduction in the administrative cost of creating a task. 

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:abe41cdbc436f2043559c26bb96d'>Package Includes</h2>

<h3 id='temp:C:abedbab36947452416198d55ca1a'><br><b><span style="color:#333333" textcolor="#333333">OmniScript (1)</span></b></h3>

<div class="" data-section-style='5' style=""><ul id='temp:C:abe00bfff535d6a4c87aea28a119'><li id='temp:C:abe5ae79e245c4c4435b6f6561c0' class='' value='1'><span style="color:#181818" textcolor="#181818">createtask</span>

<br/></li></ul></div><h3 id='temp:C:abee66c9789a31a4da59044e11a0'><b>DataRaptor (6)</b></h3>

<div class="" data-section-style='5' style=""><ul id='temp:C:abede2d1eae4352447390b1dc59d'><li id='temp:C:abe7282a600d50e4040a367c45a7' class='' value='1'>ContactCenterContectObjectIDExtract

<br/></li><li id='temp:C:abe97cf6ce4384b4ee0922b43f00' class=''>ContactCenterCreateTask

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:abe4d8eebf7eb8d4bf885f6af9eb'>Configuration Requirements</h2>

<h3 id='temp:C:abe02c3c1323ce3474ea66b32a62'>Installation Instructions:</h3>

The following steps are required for installation.<br/>

<h4 id='temp:C:abee73e3008f2ee45fc92e44e0a2'>Install the Data Pack</h4>

<div data-section-style='6' class="" style=""><ul id='temp:C:abe5a574921db3f4445a9e29980c'><li id='temp:C:abe94fa4df6823f47c281906cc79' class='' value='1'>The Data Pack folder in the following GitHub repository contains one (1) DPA Data Pack. Please download the Data Pack and save them to your desktop: <a href="https://github.com/HLS-Accelerate/contact-center-task">https://github.com/HLS-Accelerate/contact-center-task</a>

<br/></li><li id='temp:C:abebe8195cc9173479fb2cb4fce6' class='parent'>Then, complete the following steps to import them into your Salesforce org.

<br/></li><ul><li id='temp:C:abebc7d97ed0d3e4aae94b59848e' class=''>To Import, in your destination Salesforce org, Click on <b>App Launcher</b> → Search for '<b>OmniStudio DataPacks</b>' and click on it.

<br/></li><li id='temp:C:abea447b552092441d9802989939' class=''>Click on '<b>Installed</b>' and on the right side click on '<b>Import from</b>'.

<br/></li><li id='temp:C:abe8b7aa9eea1204400b9ab743bc' class=''>Select '<b>From File</b>' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '<b>Install</b>'.

<br/></li></ul></ul></div><hr style='width:100%'><h2 id='temp:C:abed382d2cdc25648d68ec8ee399'><span style="color:#333333" textcolor="#333333">Assumptions</span></h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:abe480ed4b5af89461a98b7ab2ae'><li id='temp:C:abe2b558f00f0004cf381c61db9b' class='' value='1'>A customer has licenses for Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.

<br/></li><li id='temp:C:abe73f6e6333d3f4ce8adea24bec' class=''>A customer is assuming Salesforce Lightning Experience — not Classic.

<br/></li><li id='temp:C:abea852c6777ec64e42a4f07a0be' class=''>Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.

<br/></li><li id='temp:C:abe78b81d21ee414dab84e82ffe0' class=''>The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved. 

<br/></li></ul></div><hr style='width:100%'><h2 id='temp:C:abe689fd8b2c96a4f23944ffea5a'>Revision History</h2>

<div class="" data-section-style='5' style=""><ul id='temp:C:abede75ed6f2a7f44e795144e878'><li id='temp:C:abe4f94811fb4fe410f9de9cd09f' class='' value='1'>June 21, 2022
