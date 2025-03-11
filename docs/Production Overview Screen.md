# **Production Overview Screen**
Within the Production Overview Screen, users interact with two primary tabs: (1) Sites, and (2) Equipment. These tabs serve as focal points for accessing and analyzing production data. The functionalities embedded within these tabs are designed to streamline data exploration processes.

## **Filtering Capabilities**
Central to the user interface are dynamic filtering mechanisms housed within both tabs. Positioned at the top, these filters enable users to refine the displayed content based on their specified criteria.

## **Sites Tab**
The site tab provides users customizable information for sites in the EXCO system. Each site entry within the Production Overview Screen can be expanded to reveal trend analysis associated with the values attributed to that site. Additional filter options exist on the page to allow users to filter by input.

![image](https://github.com/user-attachments/assets/c3496c5b-76d3-4660-b45e-6c118eb882c7)
/// caption
Site Tab
///

### **Sort & Total Column**
The site tab includes a sorting dropdown functionality, allowing users to organize data by column headers. This feature not only facilitates data organization but also aggregates totals from the selected column, providing users with comprehensive insights into the dataset.

![image](https://github.com/user-attachments/assets/bde63514-e970-43c3-9c01-eb8bd452f760)
/// caption
Sort & Total value Filter
///

### **Data Exports**
Users have the option of exporting site data from the production overview screen. The export functionality includes associated name spacing based on filter selections. Users can export site data by clicking on the ‘Export Data’ button in the bottom right corner.

### **Well Hammer**
To use the well hammer, users must select a filter at or below ‘Area’. If filters are NOT selected, the ‘Well Hammer’ button will be greyed out and will provide the prompt to select a filter. Once filtered, users can select sites that have wells and click on the ‘Well Hammer’ button to open the hammer dock.

The well hammer dock is broken into two parts: (1) the selected wells and (2) the audit log. All selected wells will appear in the ‘Wellheads to Hammer’ table. If a user selects a site that does NOT contain a well to hammer, the dock will provide a notification that the selected site will not be included due to a lack of proper equipment. Users will be prompted with an additional confirmation when clicking the ‘Hammer Wells’ button. The audit log is located at the bottom of the well hammer dock. The bottom area will display all previous hammered wells.

![image](https://github.com/user-attachments/assets/f092c74b-1d48-4fd0-b196-e59e536c02f8)
/// caption
Well Hammer Dock Functionality
///

### **Choke Hammer**
To use the choke hammer, users must select a filter at or below ‘Area’. The ‘Choke Hammer’ button will be greyed out if no filter is selected. Once filtered, users can select sites that have chokes and click on the ‘Choke Hammer’ button to open the hammer dock.

The choke hammer dock is broken into 3 parts: (1) the selected sites, (2) the editor, and (3) the audit log. All selected wells will appear in the top table. If a user selects a site that does not contain a choke, the dock will provide a notification that the selected site will not be included due to a lack of proper equipment. PID setpoint values can be changed in this dock. Any changes users make to the mode, setpoint, or output are reflected in the top table. After making changes users can either finalize their changes by clicking on ‘Submit Changes’ or revert the values back by clicking ‘Revert’. Users will be prompted with an additional confirmation when clicking the ‘Hammer Chokes’ button. The audit log is located at the bottom of the choke hammer dock. The bottom area will display all previous hammered chokes and changes made in the editor.

![image](https://github.com/user-attachments/assets/e47b5883-fc34-45d4-bd7a-37c7d972e46a)
/// caption
Choke Hammer Dock Functionality
///

### **SPOC Hammer**
The ‘SPOC Hammer Dock’ is broken into 2 key segments: (1) The SPOCS to Hammer List, and (2) Audit Log. All selected sites that house SPOCs will be listed in the SPOCS to Hammer List. Any changes made to equipment (Start or Stop) will be logged in the bottom table. 

To use the SPOC Hammer, users must select a filter at or below ‘Area’. Once filtered, users can select sites that have SPOCs and click on the ‘SPOC Hammer’ button to open the hammer dock. If filters are not selected the ‘SPOC Hammer’ button will be greyed out and will provide the prompt to select a filter.

![image](https://github.com/user-attachments/assets/57466359-764e-4617-9a5b-aec8af19424c)
/// caption
SPOC Hammer Dock Functionality
///

## **Equipment Tab**
The equipment tab allows users to view all equipment within the EXCO system. The equipment tab includes a filter dropdown menu, enabling users to select specific equipment for a detailed view. Each selection of equipment has a set of standard columns to display important information. Equipment column preferences made in the ‘User Settings’ are reflected on this screen.

![image](https://github.com/user-attachments/assets/3983a212-84cb-4dc9-9df1-78f5c9d91fa8)
/// caption
Equipment Tab
///

### **AutoChoke Equipment Display**
AutoChoke equipment can be selected under the Equipment Tab in the Production Overview screen. Users need to select an Asset, Area, or Site to display associated AutoChoke information. 

![image](https://github.com/user-attachments/assets/41acef35-4aa2-441c-8163-830354353627)
/// caption
Asset, Area, or Site Selection Requirement
///

AutoChoke information is displayed on a per-site basis. By default, columns will display even if data is not present for certain features. For example, Rate-02 columns indicate the existence of a second AutoChoke on a site, but the column will display even for sites with a single AutoChoke. 

![image](https://github.com/user-attachments/assets/bea63a99-f0ab-4c93-99b5-fafe4217d819)
/// caption
General Functionality
///

Users can modify the displayed columns via the ‘Column Config’ button. Clicking on the ‘Column Config’ button will open the column configuration dock. Users can check/uncheck the column name to show/hide the respective column. Changes to the column configuration will reflect to the screen after clicking on ‘Update Column Visibility’. 

![image](https://github.com/user-attachments/assets/9f6603ae-1a95-4a25-b6e2-c94d606854de)
/// caption
Column Configuration
///

By default, users can sort AutoChoke equipment via Site Name or Max Rate. Specific column sorting can be selected via the ‘Sort & Total Column’ drop down list at the top of the screen. Selections made here will automatically reflect in the screen. 

![image](https://github.com/user-attachments/assets/270cd2fd-d810-4c59-bb06-dc6854c5ff3d)
/// caption
Sort Example
///

Users can save their column configuration by clicking on the ‘Save’ icon in the top right corner. Saved column configurations stay persistent throughout new sessions after saved. Users can export data by clicking on the ‘Export Data’ button in the bottom right corner. The exporting process will display which row is currently being exported out of the total row count. All exported data will download in a .CSV format. 

![image](https://github.com/user-attachments/assets/479f7c70-eabe-4955-823c-4f5678056ba5)
/// caption
Export Indication
///

_Note: East Texas NLA (ETXNLA) is the only Asset which will display AutoChoke data._

### **Tank Equipment Display**
Tank equipment can be selected under the Equipment Tab in the Production Overview screen. Users will need to select an Asset, Area, or Site to display associated Well information. 

![image](https://github.com/user-attachments/assets/485254c2-5685-491f-a892-1b640ee0c831)
/// caption
Asset, Area, or Site Selection Requirement
///

Tank information is displayed on a per-site basis. By default, columns will display even if data is not present for certain features. 

![image](https://github.com/user-attachments/assets/81625f4f-0df9-4c1b-ab87-1abf99aa34c0)
/// caption
General Functionality
///

Users can modify the displayed columns via the ‘Column Config’ button. Clicking on the ‘Column Config’ button will open the column configuration dock. Users can check/uncheck the column name to show/hide the respective column. Changes to the column configuration will reflect to the screen after clicking on ‘Update Column Visibility’. Column configurations can be set to each asset via the asset selection. This feature allows users to have different column configurations depending on which asset they are viewing. 

![image](https://github.com/user-attachments/assets/9262942c-86c2-468c-8a6a-6728010f858c)
/// caption
Column Configuration
///

By default, users can sort Tank equipment via Site Name or Device ID. Specific column sorting can be selected via the ‘Sort & Total Column’ drop down list at the top of the screen. Selections made here will automatically reflect in the screen. 

![image](https://github.com/user-attachments/assets/44ee0a9d-f3f6-47a8-ac5e-0896b75059ef)
/// caption
Sort Example
///

Users can save their column configuration by clicking on the ‘Save’ icon in the top right corner. Saved column configurations stay persistent throughout new sessions after saved. Users can export data by clicking on the ‘Export Data’ button in the bottom right corner. The exporting process will display which row is currently being exported out of the total row count. All exported data will download in a .CSV format. 

![image](https://github.com/user-attachments/assets/bf9c986a-1c66-4581-b90f-2a1998f12761)
/// caption
Export Indication
///

