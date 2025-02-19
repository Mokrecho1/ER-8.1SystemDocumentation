# **Production Detail Screen**
The Production Detail Screen serves as an interface for users to access and manage site-specific details. It offers various functionalities to monitor equipment status, access detailed information, and configure settings. Equipment cards dynamically hide, and show based on specific site criteria.

![image](https://github.com/user-attachments/assets/2b23edac-a372-4d2f-b612-25f3a7050f14)
/// caption
Production Detail Screen
///

## **Accessing the Production Detail Screen**
Users can access the Production Detail Screen through two (2) primary methods:

· **Double-click:** Users can double-click on a site from the production overview to access the Production Detail Screen.

· **Navigation Bar:** Users can navigate to the Production Detail Screen from the left-hand tree interface.

## **Standard Features**
The following section breaks down standard features users can find across all production detail screens.

### **Check-In Options**
The Check-In feature on the production detail screen allows users to specify site or Cr visit options. Users can check in by clicking the “Check In” button. Check ins are separated into three (3) types: (1) Site Visit, (2) CR Visit, and (3) Pad Visit. Clicking ‘Check In’ will open a new window to select the visit type and enter any notes. Previous visits are noted in the same card.

![image](https://github.com/user-attachments/assets/9cac9252-98a5-46c3-a638-3c86ca114138)
/// caption
Site Visit Check In
///
![image](https://github.com/user-attachments/assets/07e18d43-37b8-48cf-a00b-b768233c8c7f)
/// caption
Site Visit Pop Up
///

### **Note Management**
Users can add site specific notes in the bottom left note card. Notes added to the detail screen can be pinned to the bottom of the text box by clicking the ellipsis (…) next to a note. Users can delete or edit pins via the same ellipsis (…).

![image](https://github.com/user-attachments/assets/57824fbb-6d24-40ff-ad8b-8d0c5d5f9f11)
/// caption
Note Functionality
///

Users can click on the ‘ellipsis (…)’ next to a note they have created to open the ‘Edit’ popup. In this popup users can edit their note and change the note’s timestamp. Any changes to the timestamp will be displayed via a yellow highlight within the popup. Users can submit changes by clicking ‘Submit Edit’. Changes to the timestamp will automatically move the note back to the respective time in chronological order. 

![image](https://github.com/user-attachments/assets/2dc7b621-9206-4620-b3d3-1bb5239342e3)
/// caption
Note Modification
///

### **Alarm Visualization**
Alarm colors are displayed on equipment cards, providing users insight into equipment status and potential issues. The following table provides current color use and alarm indication:

| **Color** | **Alarm Indication** |
| ----- | ---------------- |
| **Blue** | Low |
| **Yellow** | Medium |
| **Orange** | High |
| **Red** | Criical |

### **Equipment Cards**
Each equipment card displays essential details including tag, value, tag path, and spark line, facilitating quick monitoring and analysis. Each card features a detail button that opens a swing dock, offering additional options such as trending and detailed information.

![image](https://github.com/user-attachments/assets/622f210b-4023-4172-b80e-d5d12cd9ab26)
/// caption
Equipment Card Functionality
///

## **Well Status**
The Well Status dock allows users to adjust the current identified status on a specific well. Users can open the well status dock by clicking on the pen icon to the right of ‘Status’ on a well card. The well status dock allows users to select a status and set an expiration duration for the status. Users can quickly select a set range of dates (1 day, 7 days, 30 days, or 60 days), or they can enter a specific date and time using the calendar feature. To finalize any changes to the status, users will need to click ‘Submit’ at the bottom of the dock.

![image](https://github.com/user-attachments/assets/4c193ebd-4196-414d-a416-8653a4056419)
/// caption
Well Status Functionality
///

### **Alarm Configuration**
Users can configure alarm settings for equipment cards by right-clicking and accessing options such as enabling / disabling alarms, setting priority levels, selecting modes, and specifying setpoints. The alarm configuration dock is only accessible through this right-click function.

![image](https://github.com/user-attachments/assets/b0b60997-896c-4ad2-bbb4-0b2aeec6c044)
/// caption
Alarm Configuration Functionality
///

### **Trending**
The global trend enables users to visualize trends across multiple equipment cards. Users can add equipment cards to the global trend by right-clicking and selecting the appropriate option.

![image](https://github.com/user-attachments/assets/0273b70f-d88b-4bf9-84d3-77cb4a4aa882)
/// caption
Trending Functionality
///

When users add tags to the global trend, tags will populate a table at the bottom of the dock. The table allows users to quickly locate a trending tag and manipulate it if needed. Tags can be hidden, edited, or deleted from the trend dock table.

![image](https://github.com/user-attachments/assets/2c840f24-5eb8-4078-9360-abd58f53a8b0)
/// caption
Pen Editor
///

### **Right-Side Button Functionality**
The right side of the production detail screen provides seven (7) standard buttons which provide additional supporting options for users. All buttons aside from the ‘Demand Poll’ and ‘Water Alert’ will provide an additional dock.

#### **Demand Poll**
The ‘Demand Poll’ button allows users to poll tag values instantly, facilitating real-time data retrieval and analysis.

#### **Safety**
Safety values visualization provides a comprehensive overview of alarm status. This dock allowing users to review setpoints, current values, and the most recent active alarm. Tabs at the top of the dock correspond to specific equipment, providing users access to setpoints and additional information.

![image](https://github.com/user-attachments/assets/757f18ee-6e97-4e85-ba7b-0031ff4c964d)
/// caption
Safety Dock
///

The indicator provided next to each card identifies the status of the alarm. A grey circle indicates there is no safety enabled for that equipment. A green circle indicates that the equipment has no current active alarms. A red circle indicates an alarm is currently active on that equipment.

The ‘Remote Well Bring Online’ feature allows users to bring wells back online after a shut-in. The ‘Well Bring Online’ feature can be accessed via the site’s safety dock. When a well is NOT shut-in the bring online features will be disabled for interaction. A 15-minute timer begins once a well gets shut in. Once the 15-minute timer is over, the system will check to see if there are any alarms that are currently active. 

![image](https://github.com/user-attachments/assets/e427d410-28c2-43e2-8ae0-c61995d269aa)
/// caption
Bypass Example
///

If there are no alarms active, the bring online buttons will enable in sequential order: (1) Bypass, (2) Reset, and then (3) Normal.

•	Bypass will demand poll the well.

•	Reset will reset the device.

•	Normal will restore the well to typical functionality. 

![image](https://github.com/user-attachments/assets/a5ef0060-5831-47d1-9020-b463dcabc1d3)
/// caption
Bypass Process
///

#### **Polling Frequency**
The ‘Polling Frequency’ button automates the population of frequency settings. This dock enables users to customize intervals and expiration dates according to their requirements, enhancing flexibility and efficiency in data polling. Intervals can be set up to one (1) hour. Users can establish expiration dates via the calendar card in the dock. Users can finalize their changes by clicking ‘Submit’. Once an interval is set, an expiration date is provided at the bottom of the dock.

![image](https://github.com/user-attachments/assets/5a02dea0-bcd6-4d89-9ace-7e5a6e518c3d)
/// caption
Polling Frequencies Dock
///

Tags that poll at 1-minute intervals require a lot of bandwidth. On certain sites, fast polling is available to reduce bandwidth by throttling general polling frequencies and establishing ‘fast poll’ tags. To access fast polling users will need to navigate to the Polling Frequency dock. From there, the site’s default polling interval can be set to a slower rate. If enabled, fast polling can be accessed via the ‘Fast Poll Mode NOT Active’ hyperlink. This link will open the ‘Fast-Polling Frequency’ dock.

![image](https://github.com/user-attachments/assets/cdb6b9f8-f6b7-40c3-bea9-1921034c7166)
/// caption
Fast Poll Hyperlink Location
///

The ‘Fast-Polling Frequency’ dock provides users a list of site selections and a list of sites that are currently fast polling. Users can search for the specific site on the left side table and move it to the fast-polling list via the central move arrows. Polling frequencies for the fast-polling list can be changed at the top of the table. Once a site has been moved over, users can click on ‘Submit’ to commit all moved sites. Any submissions made will be listed in the audit table at the bottom of the dock.

![image](https://github.com/user-attachments/assets/df9a2684-a72b-4e2d-8e07-305c1a9e8eb7)
/// caption
Fast Poll Dock
///

#### **VO Tickets**
The VO report button provides a sub-view (duplicate) of the VO Ticket screen, offering detailed insights into production tickets per site. The dock acts as a visualizer of the VO Ticket screen. For more information about VO Tickets click here.

![image](https://github.com/user-attachments/assets/7188f31e-f35f-492e-ad5a-fdc08e4aacc5)
/// caption
VO Tickets Dock
///

#### **Global Trend Button**
The global trend enables users to visualize trends across multiple equipment cards. Users can add equipment cards to the global trend by right-clicking and selecting the appropriate option. Adding equipment cards in this fashion will open the global trend dock from the bottom of the screen. Users can click on the ‘Global Trend’ button if they need to access the trend without wanting to add new tags.

![image](https://github.com/user-attachments/assets/a039f8fa-7b43-45de-a9ee-cdfe03cb3874)
/// caption
Global Trend Access
///

#### **Well Site Trend**
The Well Site Trend enables users to visualize trends across a set of specific well tags. Users can enable or disable certain equipment from the right-side list. All filtering and date range options that exist within the Global Trend are mirrored here. Within the Well Site Trend dock, users can customize the display of trending data. Changes made to the User preferences for displayed tags and coloration will redraw trend lines. Users can change trend color by clicking on the associated circle next to each tag selection. This will open a color swatch at the bottom of the user preferences. 

![image](https://github.com/user-attachments/assets/501a403e-22f6-40ef-b895-aa3ac217c3ae)
/// caption
Well Site Trend - Dark Mode Enabled
///

Making a color selection closes the swatch and updates the respective coloration. All modifications made to color and display are permanent. Changes carry over between well site trend screens. Users can hover the mouse over any trend to display a popup with associated tag information. 

![image](https://github.com/user-attachments/assets/fe2d833d-3155-4508-a6e0-ad9bf998249c)
/// caption
Well Site Pop Up
///

Users can access the ‘Local Pen Control’ via the bottom left button. Here modifications to pens can be made and analysis tools will display any selection results. Changes made within the ‘Pen Control’ are temporary and will not move between well site trend instances. 

![image](https://github.com/user-attachments/assets/d1c977d9-9869-4012-a5f6-fe9993c6e38f)
/// caption
Well Site Trend Pen Editor
///

#### **Site Event History**
The ‘Site Event History’ dock enables users view actions made on specific equipment on a site. The docket provides information on the action made, the target equipment, when it was done, and what value was changed. This docket acts as an audit log for other operators.

![image](https://github.com/user-attachments/assets/74bc9856-17fc-430f-a740-2656b5c7d22e)
/// caption
Event History Dock
///

#### **Water Alert**
The ‘Water Alert’ button provides users the ability to alert water services for tank drainage. Clicking on the ‘Water Alert’ button will notify the user with a confirmation before sending an email to the water services.

![image](https://github.com/user-attachments/assets/e5b91d16-2efa-4c1c-9ff5-ff1e5d250c5d)
/// caption
Water Alert Example
///

*Note: Water Alert is only available on sites that include Water Tanks.*

## **Cards & Docks**
The production detail screen populates specific cards depending on site filter selection. Cards have detail buttons that provide additional information or functionality depending on the card type. The following section breaks down specific card types that have particular dock functionalities outside of generic detail information.

### **SPOC Card**
The ‘SPOC’ dock provides users the ability to start or stop the equipment and view general details. Users can edit existing values on the dock by clicking on the ‘pen’ icon to the right of the value. All editable values will have a ‘pen’ icon available. A pop-up will appear after clicking on the pen icon to input a new value.

![image](https://github.com/user-attachments/assets/d063df56-f8d7-4809-9cf2-5018c3ea49f6)
/// caption
SPOC Card Functionality
///

‘SPOC Revelation’ card docks allow the user to do a remote reset of a SPOC device. Users can access the dock by clicking on the detail button on a SPOC Revelation card. In the center of the ‘Control’ panel the remote reset button will allow SPOC resets. This is a dual confirmation process requiring consent to be given twice. Confirming both prompts will send a reset command to the respective reset tag. 

![image](https://github.com/user-attachments/assets/4a2d8fe2-3bb6-4ed5-825a-ebf020580caf)
/// caption
Remote Reset Functionality
///

### **Autochoke Card**
The ‘AutoChoke’ dock provides users the ability to change autochoke functionality and view configurations. Setpoint values and modes can be changed by clicking on the ‘pen’ icon next to each entry.

![image](https://github.com/user-attachments/assets/d999217a-4ae8-4f92-be4e-f3e3c835a87c)
/// caption
Autochoke Dock Functionality
///

### **Plunger: Smart Intermitter**
The ‘Smart Intermitter Plunger’ dock provides users the ability to view plunger information and establish shut in. The dock is separated into two lists which include data sourced from the plunger. At the top of the dock the user is provided four (4) buttons which all relate to shut in functionality. The following table provides descriptions for each button:

| **Button Name**          | **Description**                    |
| ------------------------ | ---------------------------------- |
| **24 Hour SIPB**         | Shuts in the plunger for 24 hours. |
| **48 Hour SIPB**         | Shuts in the plunger for 48 hours. |
| **Custom SIPB**          | Custom user set shut in timer.     |
| **Cancel Shut In Timer** | Cancel any active shut-in timer.   |

![image](https://github.com/user-attachments/assets/fe752d7e-1cab-4109-bdc2-d102af76d0f7)
/// caption
Smart Intermitter Detail Dock
///

Users can edit existing values on the dock by clicking on the ‘pen’ icon to the right of the value. All editable values will have a ‘pen’ icon available. A pop-up will appear after clicking on the pen icon to input a new value.

### **Plunger: Intermitter**
The ‘Intermitter Plunger’ dock provides users the ability to view plunger information and establish shut in. The dock is a singular list which includes data sourced from the plunger. This plunger type includes limit and timer values parallel to one another.

At the top of the dock the user is provided four (4) buttons which all relate to shut in functionality. The following table provides descriptions for each button:

| **Button Name**          | **Description**                    |
| ------------------------ | ---------------------------------- |
| **24 Hour SIPB**         | Shuts in the plunger for 24 hours. |
| **48 Hour SIPB**         | Shuts in the plunger for 48 hours. |
| **Custom SIPB**          | Custom user set shut in timer.     |
| **Cancel Shut In Timer** | Cancel any active shut-in timer.   |

![image](https://github.com/user-attachments/assets/2755b127-a5a3-4459-a7ef-ad30bed3bca7)
/// caption
Intermitter Detail Dock
///

Users can edit existing values on the dock by clicking on the ‘pen’ icon to the right of the value. All editable values will have a pen icon available. A pop-up will appear after clicking on the ‘pen’ icon to input a new value.

### **Cooler**
The ‘Cooler’ dock provides users the ability to view cooler information and toggle the switch status. Users can either disengage or engage the cooler equipment. The status of the cooler is also displayed to the user. Generic detail information is held on the ‘Detail’ tab within the dock.

### **ESD Valve**
The ‘Emergency Shut Down (ESD) Valve’ dock provides users the ability to view valve information and trigger an ESD of the valve. The ESD valve dock is separated into two sections: (1) the ESD trigger/reset, and (2) the audit log. Users can identify if the ESD is clear and if an ESD needs to occur with the graphic at the top of the dock. Any selection made by users, be it triggering the ESD or resetting, is logged in the bottom table

### **Expansion Docks**
Certain docks within the interface offer expansion capabilities, enabling users to visualize data without the need for scrolling or reliance on built-in tabs. Expansion docks provide an efficient means to view all relevant information on a single screen.

Users can identify expandable tabs by locating the resizing bar attached to the dock. This resizing bar serves as a visual indicator, signaling the potential for expanding the tab to accommodate additional content. To expand a dock, users can click and drag the resizing bar to the desired size. The dock will automatically adjust to the user’s selected size preference.

![image](https://github.com/user-attachments/assets/20dfcd08-a11a-4209-abcc-bc890ff5f530)
/// caption
Expanding Dock Example
///

## **Global Register Editing**
The ‘Global Register’ dock allows users to change a tag’s device ID communication, register reading, and polling frequency. Users can access the Global Register dock by right-clicking on any value and selecting ‘Edit Register’. 

![image](https://github.com/user-attachments/assets/8280e980-7996-42f4-8c38-a995d0d6f667)
/// caption
Global Register Editing Functionality 
///

The editor displays the device tag path, the device ID, register, and polling interval. Display options have an entry box or drop-down menu for editing. Any edit made will be displayed with a yellow highlight. The ‘Refresh’ and ‘Submit’ buttons will only be interactable once an edit is made. Users can click on the ‘Refresh’ button to default the changed fields back to their original entry. Users can press ‘Submit’ to push any changes to the tag. Any submissions made will be listed in the audit table at the bottom of the dock. 
