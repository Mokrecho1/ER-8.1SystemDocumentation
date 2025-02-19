# **Comms Overview Screen**
The ‘Comms Overview Screen’ provides users the ability to monitor communication devices. The screen consists of a singular table that is dynamically impacted by the header filter selection. Users can view the name, voltage, status, last poll, and last poll attempt to diagnose errors or analyze communication devices. Tag paths for communication devices display as a tooltip once the user hovers their mouse over the device entry.

![image](https://github.com/user-attachments/assets/93bbc622-da54-4c07-8d6f-b87f6b07cb18)
/// caption
Communication Device Table
///

Notification colors are displayed on communication device entries, providing users insight into communication status and potential issues. The following table provides current color use and indication:

| **Color**        | **Indication**               |
| ---------------- | ---------------------------- |
| **Grey / Black** | Null Tag Input               |
| **Magenta**      | Bad Communication Connection |

## **ACM Communication Configurator**
Select users have access to changing the IP and Port of devices from the ‘Comms Overview’ Screen. Once users select a row in the table, an ‘Edit Address’ button will appear in the top right corner. This button opens a popup displaying all remote devices associate with that selected entry.

![image](https://github.com/user-attachments/assets/8cfc6b41-75cc-49d7-aa10-f10efc5fedc6)
/// caption
Edit Address Selection
///

The popup allows the user to change the IP Address and Port for all listed devices. The ‘Submit’ button will only be interactable once an edit is made. Any submissions made will be listed in the audit table at the bottom of the dock. 

![image](https://github.com/user-attachments/assets/7df0eb19-c361-4af2-ba3c-613174dc4237)
/// caption
Communication Configuration Pop Up
///
