# **Dashboard Screen**

The dashboard acts as the landing page for users. The screen serves as a centralized and customizable hub where users can quickly assess critical information without needing to navigate to different screens. The dashboard screen incorporates a flexible widget system that allows users to customize their visual experience according to their workflow requirements. This system allows users to resize, move, remove, and add various widgets. Unlike other screens, the dashboard is not impacted by any filter selections made by the user. This ensures that users always have access to a consistent set of information regardless of adjustments or prior selections.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen1.png?raw=true)

## **Dashboard Access**
Users can access and view dashboards created by other operators. The dropdown menu in the top left allows users to view and select possible dashboards. Dashboards available to view are identified by the operator’s Ignition username.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen2.png?raw=true)

The selection system allows users to copy other dashboard layouts to their own dashboard. If a layout is copied over, the dashboard selection will reset to the user’s dashboard (‘My Dashboard’).

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen3.png?raw=true)

*Note: Layout copying overwrites all widget placements, sizing, and information and CANNOT be reverted.*

## **Widget System**

The widget system offers a flexible way to customize the dashboard layout and content. Users can access the widget management system through the top right toggle to tailor their dashboards according to preferences and needs. To access the widget system users can click the toggle to ‘Move/Resize’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen4.png?raw=true)

## **Edit Mode**
When entering edit mode, a grid overlays the dashboard, indicating potential locations for widget placement. Each square within the grid presents an opportunity to add a widget. By clicking on any square within the grid, a widget list appears, indicating available options. Visual cues such as greying of the box and a plus sign highlight areas where widgets can be added. Once a widget is selected and added, the user can freely move, resize, or delete it to suit preferences and optimize the dashboard's layout. Widgets dynamically scale to accommodate changes in layout and content, ensuring a seamless and responsive user experience. Widget configurations are not available in edit mode.

| Widget Manipulation	| Description |
| --------------------| ----------- |
| Moving Widgets |	When moving widgets, a dashed shadow outlines the squares the widget will occupy. This provides the user with a clear visual representation of where the widget will be placed.
| Resizing Widgets | Multiple grab points are provided, allowing for dragging the widget and adjusting its size according to requirements.
| Deleting Widgets | To remove a widget, click on the (x) located in the top right corner of the widget card. This action deletes the widget from the dashboard.
| Stacking Widgets | Widgets can be placed above one another, allowing for efficient use of dashboard space.

### **Alarm Overview Widget**
The Alarm Overview widget displays the number of medium, high, and critical alarms in an Asset. Users can change the selected asset by right clicking on the widget and selecting the respective asset.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen5.png?raw=true)

### **Alarm Status Table Widget**
The Alarm Status widget acts as a mirror of the alarm overview screen. This widget allows users to view any active or shelved alarms typically viewed in the alarm overview screen. For more information on alarm overview functionality, view the ‘Alarm Overview Screen’ page.  

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen6.png?raw=true)

### **Equipment Card**
The Equipment Card widget displays an overview of equipment information for a selected equipment type. Users can change the selected equipment via the top left drop-down menu. The card will dynamically change in the display depending on equipment selected. Filter configuration is available via right-clicking.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen7.png?raw=true)

### **Haynesville Line Pressure**
The Haynesville Line Pressure widget is a static information card that displays pressure information in three (3) specific areas: (1) Holly 3 Waukesha, (2) Williams, and (3) Shelby 3.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen8.png?raw=true)

Only certain users will have access to the ‘pens’ to change the values displayed on the widget. Clicking on the pen icon will give users a drop-down selection for other values. Making a change will impact all widgets across all users. 

![image](https://github.com/user-attachments/assets/2334b120-022b-4cf3-89aa-e2f25edeae56)

If the widget is enlarged it will display the trends for the selected line pressures. 

![image](https://github.com/user-attachments/assets/cd2e80c6-e53b-4f24-88db-456429f82e19)

### **My Tags & Trends Widget**
The ‘My Tags & Trends’ widget has two functionalities: (1) to bank and view tags values, and (2) to view banked tags as trends. Users can change the widget functionality by right clicking on the widget and selecting ‘Switch to Functionality’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen9.png?raw=true)

Users can bank tags by right clicking on any tag value in the EXCO system and selecting ‘Send Tag to Dashboard’. If a user does NOT have the ‘My Trend’ widget on their dashboard, sending tags will be saved to the user profile and will populate the widget when selected. Tags can be removed from the tag bank by right clicking on the widget and selecting ‘Remove Tags’.

*Note: Users can have multiple of the same widget active in their dashboard. For example, if a user wants to view both the banked tags and the trend, two ‘My Trend’ widgets can be active at once.*

### **Potential Vs. Actual Widget**
The ‘Potentials Vs. Actual’ widget provides users a view of Target and MCFPD rates for filter selections. Users can right-click to filter the display from Company down to a specific Facility. Data can be refreshed by clicking on the ‘Cycle’ icon in the top right corner.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen10.png?raw=true)

### **Roll Up Overview Widget**
The ‘Roll Up Overview’ widget has two functionalities: (1) View roll-up data for assets, and (2) view roll up data for areas. Users can change the widget functionality by right clicking on the widget and selecting ‘Switch to Functionality’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen11.png?raw=true)

Users can select the asset/area roll up selection by right clicking on the widget and navigating to the ‘Select Rollups’ menu. Any selected asset/area will have a check mark in the roll up menu. Area selections can be made by either selecting the specific area or selecting an asset to add all associated areas.

### **Singular Value Widget**
The ‘Singular Value’ widget allows users to visualize a single banked tag (for more information on banked tag, see the ‘My Trends Widget’). Users can select the single tag by right clicking the widget and selecting ‘Change Value’. All banked tags will appear under the ‘Change Value’ menu. Tags can be removed from the widget by right clicking on the widget and selecting ‘Remove Tags’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen12.png?raw=true)

### **Top 10 Well Widget**
The ‘Top 10 Wells’ widget shows the user a selection of top 10 wells based on MCFD. Users can filter the displayed wells by right clicking the widget to access the selection menu. The selection menu is broken into two filter options: (1) tag provider, and (2) area. The ‘area’ selection in the menu will dynamically change to the tag provider the user selects. For example, if a user selects the area ‘Appalachia’, the list will include ‘Central 1’, ‘Central 2’, ‘Williamsport East’, and ‘Williamsport West’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen13.png?raw=true)

### **Favorite Sites**
The ‘Favorite Sites’ widget will display a list of the user’s favorited sites. Users will need to select sites on the ‘Site Overview’ screen and right-click to add to their favorites. Favorite sites can be removed from the widget by right clicking on a site entry and selecting ‘Remove – [Site Name]’.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen14.png?raw=true)

Selected sites can be added one by one or all at once via the right-click menu.

### **Hot Wells**
The ‘Hot Wells’ widget displays a list of wells identified as ‘Hot’. Well identification pulls from site metadata. If an alarm is active on any hot well, the entry will turn red. As with other widgets, right click configuration is available for filtering.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen15.png?raw=true)

### **Sticky Note Widget**
The ‘Sticky Note’ widget allows users to leave notes on their dashboards. Any notes added to the ‘Sticky Note’ widget is tied to the user’s account. Users will only be able to view their notes regardless of which dashboard they are on.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen16.png?raw=true)

### **Weather Widget**
The ‘Weather’ widget allows users to view weather and location data depending on their zip code. Users can change the widget zip code by right-clicking, selecting ‘Toggle Configure’, and entering a zip code in the widget when prompted.

![Image title](https://github.com/Mokrecho1/ER-8.1SystemDocumentation/blob/main/docs/Images/dashboardscreen17.png?raw=true)

## **Multi-Dashboard Support**
Multi-dashboards are available via tabs at the top of the Dashboard screen. The default dashboard the user has created (my dashboard) will populate under ’Tab 01’. ‘Tab 01’ is the default dashboard tab that will display when navigating to this screen.

![image](https://github.com/user-attachments/assets/4729b9f8-24ce-4579-b90e-860961f3b324)

‘Tab 02’ and ‘Tab 03’ will be empty if the user has not created dashboards on those respective tabs. All functionality from the default dashboard screen exists within ‘Tab 02’ and ‘Tab 03’. Users can copy other dashboards created only within each dashboard tab. For example, a user can copy over a dashboard someone else has created on ‘Tab 02’, but that copy can only exist on ‘Tab 02’. **Dashboards cannot be copied over between tabs**. 

![image](https://github.com/user-attachments/assets/fa01b263-4acc-49a3-92bb-36d3a56455f5)

Sending cards to the Dashboard will now allow users to select which dashboard to send the card.

![image](https://github.com/user-attachments/assets/5c061bc9-cf9f-4add-bce1-8f6502853323)

## **Mobile Dashboard Support**
Dashboard support for mobile devices allow users to sort dashboard widgets by a pre-defined order.  Users can change the order of widgets on their mobile devices by clicking on the ‘Widget Order’ button in the top right corner of the screen. 

![image](https://github.com/user-attachments/assets/aa0b97eb-da8a-4346-820d-7e9908408fb5)

The widget order dock displays the current order of widgets. Users can move widgets in this order by selecting a widget row item and then clicking on either the Up or Down arrow on the right. Users must click on ‘Submit’ to save their changes to the widget order. **Widget order is applied across all dashboard tabs**. 
