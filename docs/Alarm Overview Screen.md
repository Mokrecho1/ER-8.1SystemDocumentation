# **Alarm Overview Screen**
The ‘Alarm Overview Screen’ allows operators to view active alarms within the EXCO system. This screen integrates additional filtering that allows users to view specific alarm types depending on their selection. Alarming on this screen is NOT related to filter selections made in the header, but rather from field selection boxes at the top of the screen. The alarm overview screen is broken into two tabs: (1) Alarm Status, and (2) Alarm Journal.

## **Alarm Status**
The ‘Alarm Status’ tab provides users the ability to view all alarms within the system. Visible alarms are based on filter selections made in this tab. Users can change the current filter options by clicking on the ‘filter’ icon in the top right. Users can search for specific alarms using the search bar. The search bar appears once a user clicks on the search icon in the top right. Column settings for alarm status are customizable. Users can enable or disable column visibility in the setting pop up via the gear icon.

![image](https://github.com/user-attachments/assets/7f1add4d-c869-4e88-b3ba-7e0927a63af2)
/// caption
Alarm Status Screen
///

The ‘Alarm Status’ tab has sub-tabs for ‘Active’ and ‘Shelved’ alarms. Users can identify the number of active alarms in the top left corner of the alarm status tab. The number of active alarms and shelved alarms act as the headers for the sub-tabs.

Users can acknowledge or shelve alarms by selecting the alarm from the list and clicking on the respective action in the bottom right corner. Acknowledging or shelving alarms will write the action to the ‘Alarm Journal’.

## **Alarm Journal**
The ‘Alarm Journal’ tab provides a log of alarm actions taken by users. The ‘Alarm Journal’ tab maintains all search, filter, and configuration capabilities as the alarm status tab.

![image](https://github.com/user-attachments/assets/84d74778-ff3d-44c0-bd35-906cd0101fae)
/// caption
Alarm Journal
///

## **Alarm Analysis / VO Ticket Tool**
Users can navigate to the ‘Alarm Analysis’ screen  via the ‘Alarm Overview’ tab selection. This screen provides visual data for alarms and VO tickets. If users navigate from an existing screen with global filters selected, those filters will carry over to this view. If global filters are brought over, the screen will automatically apply those filters into the displayed data. 

By default, displayed values are filtered in a 24-hour time frame. Users can change filtering options at the top of the screen. Filter options include dates and alarm priorities. Changes to filters do NOT apply to the screen automatically. Users will need to click ‘Search’ to apply filters to the screen. 

The ‘Alarm Analysis’ screen is broken down into 3 separate tabs: (1) Analysis, (2) Alarms, and (3) VO Tickets. 

![image](https://github.com/user-attachments/assets/299ded18-6c86-43f8-a4bd-2f2fbbcb1589)
/// caption
Alarm Analysis / VO Ticket Tool Screen
///

### **Analysis**
The ‘Analysis tab’ is the default view displayed when users navigate to the ‘Alarm Analysis’ page. The ‘Analysis tab’ houses data visualizations of search selections. The ‘Analysis tab’ can be broken down into 3 sections: (1) Pie Charts, (2) Histogram/TreeMap, and (3) Top 10 Graphs.

![image](https://github.com/user-attachments/assets/52310a7d-1242-4a40-a806-9caad1f15c17)
/// caption
Screen Breakdown
///

#### **Pie Charts**
The Pie Charts at the top of the screen provide users visualizations related to VO Tickets and Alarming. The first three charts (from left to right) relate to VO Tickets. The last chart related to Alarming. The VO Ticket chart values all correlate to one another. The sum of the values from chart 1 will be the same as the sum of the values from chart 2. Users can hover over either the values in the chart legend or the chart itself to see the percentage view of the values displayed. The alarm chart (far right) displays colors that associate to the alarm priority level users may see in other parts of the EXCO system. Users can click on a value within any chart legend to toggle values from display. 

![image](https://github.com/user-attachments/assets/1668227b-3580-44cb-ba39-4bc8e6759e8a)
/// caption
Pie Chart Cards
///

#### **Histogram/TreeMap**
The Histogram provides an hourly view of selected data. This component associates to the selected Pie Chart. Users can change the displayed chart by selecting the ‘bar’ icon in the top right of the Pie Chart card. Users can identify the selected chart by ‘bar’ icon being highlighted green. The coloration displayed in the Histogram will associate to the selected chart. Users can toggle the Histogram to display by day in the top left corner of the component. If the date filter is set to above a 48-hour window the histogram will automatically default to the Day view. An hour view of data is only available for time ranges less than 48 hours. 

![image](https://github.com/user-attachments/assets/59c8211d-012d-40ed-a7ec-fcb9350be29d)
/// caption
Histogram By Hour
/// 

![image](https://github.com/user-attachments/assets/8e3c1947-9bb8-4fff-a705-1e1ca203ccfe)
/// caption
Histogram By Day
///

Users can switch the Histogram to the TreeMap using the top buttons of the component. The TreeMap view is not tied to any data cards on the screen. All TreeMap information is tied to the parameters of the search selection. The TreeMap view houses 3 sub-views that can be toggled via the top left buttons in the component: (1) Equipment Type, (2) Alarm Name, and (3) Tag name. The TreeMap chart displays hierarchical data in nested rectangles. These rectangles will be named depending on the sub-view selected. Each size of the rectangle is proportional to the value of the data it represents. A data value is associated to each rectangle. 

![image](https://github.com/user-attachments/assets/9249bb5a-3bf8-43ee-a81d-1ac6f2b70435)
/// caption
TreeMap
///

#### **Top 10 Graphs**
At the bottom of this tab exist two graphs that display the Top 10 Alarms, and the Top 10 VO Tickets. Data that populates into these tables will filter based on the parameters of the search selection. 

![image](https://github.com/user-attachments/assets/1e417f2b-ea9b-4fae-9e8a-7da966063ca6)
/// caption
Top 10 Alarms & VO Ticket Tables
///

### **Alarms**
The ‘Alarms’ tab will display all alarms that have occurred during the parameters of the search selection. Users can search/filter the alarm table via the text-entry filter. Users can search by any value in any column of the alarm table.  

![image](https://github.com/user-attachments/assets/66b65143-b77a-4fd2-b277-6193359b9bd6)
/// caption
Alarm Tab
///

### **VO Tickets**
The ‘VO Tickets’ tab will display all VO Tickets that have occurred during the parameters of the search selection. Users can search/filter the VO Tickets table via the text-entry filter. Users can search by any value in any column of the VO Ticket table. Additional data such as email communication and status of the VO Ticket are displayed.

![image](https://github.com/user-attachments/assets/3bb6f0fe-8d7b-4e10-9b0d-e6bab7015ea5)
/// caption
VO Tickets Tab
///
