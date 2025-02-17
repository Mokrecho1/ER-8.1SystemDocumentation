# **Production Overview Screen**
Within the Production Overview Screen, users interact with two primary tabs: (1) Sites, and (2) Equipment. These tabs serve as focal points for accessing and analyzing production data. The functionalities embedded within these tabs are designed to streamline data exploration processes.

## **Filtering Capabilities**
Central to the user interface are dynamic filtering mechanisms housed within both tabs. Positioned at the top, these filters enable users to refine the displayed content based on their specified criteria.

## **Sites Tab**
The site tab provides users customizable information for sites in the EXCO system. Each site entry within the Production Overview Screen can be expanded to reveal trend analysis associated with the values attributed to that site. Additional filter options exist on the page to allow users to filter by input.

![image](https://github.com/user-attachments/assets/c3496c5b-76d3-4660-b45e-6c118eb882c7)

### **Sort & Total Column**
The site tab includes a sorting dropdown functionality, allowing users to organize data by column headers. This feature not only facilitates data organization but also aggregates totals from the selected column, providing users with comprehensive insights into the dataset.

![image](https://github.com/user-attachments/assets/bde63514-e970-43c3-9c01-eb8bd452f760)

### **Data Exports**
Users have the option of exporting site data from the production overview screen. The export functionality includes associated name spacing based on filter selections. Users can export site data by clicking on the ‘Export Data’ button in the bottom right corner.

### **Well Hammer**
To use the well hammer, users must select a filter at or below ‘Area’. If filters are NOT selected, the ‘Well Hammer’ button will be greyed out and will provide the prompt to select a filter. Once filtered, users can select sites that have wells and click on the ‘Well Hammer’ button to open the hammer dock.

The well hammer dock is broken into two parts: (1) the selected wells and (2) the audit log. All selected wells will appear in the ‘Wellheads to Hammer’ table. If a user selects a site that does NOT contain a well to hammer, the dock will provide a notification that the selected site will not be included due to a lack of proper equipment. Users will be prompted with an additional confirmation when clicking the ‘Hammer Wells’ button. The audit log is located at the bottom of the well hammer dock. The bottom area will display all previous hammered wells.

![image](https://github.com/user-attachments/assets/f092c74b-1d48-4fd0-b196-e59e536c02f8)

### **Choke Hammer**
To use the choke hammer, users must select a filter at or below ‘Area’. The ‘Choke Hammer’ button will be greyed out if no filter is selected. Once filtered, users can select sites that have chokes and click on the ‘Choke Hammer’ button to open the hammer dock.

The choke hammer dock is broken into 3 parts: (1) the selected sites, (2) the editor, and (3) the audit log. All selected wells will appear in the top table. If a user selects a site that does not contain a choke, the dock will provide a notification that the selected site will not be included due to a lack of proper equipment. PID setpoint values can be changed in this dock. Any changes users make to the mode, setpoint, or output are reflected in the top table. After making changes users can either finalize their changes by clicking on ‘Submit Changes’ or revert the values back by clicking ‘Revert’. Users will be prompted with an additional confirmation when clicking the ‘Hammer Chokes’ button. The audit log is located at the bottom of the choke hammer dock. The bottom area will display all previous hammered chokes and changes made in the editor.

![image](https://github.com/user-attachments/assets/e47b5883-fc34-45d4-bd7a-37c7d972e46a)

### **SPOC Hammer**
The ‘SPOC Hammer Dock’ is broken into 2 key segments: (1) The SPOCS to Hammer List, and (2) Audit Log. All selected sites that house SPOCs will be listed in the SPOCS to Hammer List. Any changes made to equipment (Start or Stop) will be logged in the bottom table. 

To use the SPOC Hammer, users must select a filter at or below ‘Area’. Once filtered, users can select sites that have SPOCs and click on the ‘SPOC Hammer’ button to open the hammer dock. If filters are not selected the ‘SPOC Hammer’ button will be greyed out and will provide the prompt to select a filter.

![image](https://github.com/user-attachments/assets/57466359-764e-4617-9a5b-aec8af19424c)

## **Equipment Tab**
The equipment tab allows users to view all equipment within the EXCO system. The equipment tab includes a filter dropdown menu, enabling users to select specific equipment for a detailed view. Each selection of equipment has a set of standard columns to display important information. Equipment column preferences made in the ‘User Settings’ are reflected on this screen.

![image](https://github.com/user-attachments/assets/3983a212-84cb-4dc9-9df1-78f5c9d91fa8)

