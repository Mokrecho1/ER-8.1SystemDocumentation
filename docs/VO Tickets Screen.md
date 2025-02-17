# **VO Tickets**
The ‘VO Ticket’ screen enables users to report production-related issues. Through the interface users can initiate the process of addressing concerns by raising operation tickets. Users can create new tickets by clicking the green plus ( + ) button in the top right. When creating a VO ticket:

· Users provide a detailed description of the problem they are experiencing.
· Users designate the relevant asset associated with the reported issue, such as a meter or a well. This selection ensures that the problem is accurately tied to the pertinent operational component.
· Users are prompted to specify the primary concern and, if applicable, select a secondary issue.

Once tickets are submitted, they are logged into the VO ticket screen where it becomes part of the comprehensive database of reported issues. Logged tickets also populate within the VO dock associated with the respective operational site. The ‘VO Tickets Screen’ has the following functionality:

· Global filters at the top of the screen.
· Fuzzy filter on the table to search by keyword.
· IM escalation selection (IM1, IM2, IM3, or All).
· View open or closed tickets.
· Add a new ticket.
· Edit an existing ticket.

![image](https://github.com/user-attachments/assets/2ad190eb-e151-4019-b9ca-1dc3572ad4da)

_Note: VO tickets are not anonymous as the operator’s username and date are logged alongside the VO ticket._

Click on the plus icon (+) to add a new ticket. To edit an existing ticket, select the respective ticket from the table and click on the ‘pen/edit’ icon. Double clicking on a ticket will allow users to edit the selected ticket. A dock will swing out from the right when adding or editing a ticket. This dock will include all information requirements.

When creating a new ticket, fields in the dock will be blank except for the assumed site name if a site is selected in the global filter. Users can change both the Site Name and Meter ID in the respective dropdowns. Both dropdowns will update each other respectively. The Asset and Area fields are NOT editable. If editing an existing ticket, the fields will automatically populate with information on the selected ticket. Each VO Ticket includes four (4) required fields notated with a red asterisk. These fields must be filled prior to ticket creation. Clicking the ‘Submit’ button will submit the current ticket. Clicking the ‘Clear’ button will clear all filled fields.

![image](https://github.com/user-attachments/assets/1ffe8336-a361-49f4-90fd-be645dfd84fd)

_Note: When creating a new ticket, ‘Status’ will be forced to Open._

## **VO Ticket Field Breakdown**
The following table provides the name and description for each field within a VO ticket:

| **Field Name**         | **Description**                                                          | **Options/Additional Information**                       |
| ---------------------- | ------------------------------------------------------------------------ | -------------------------------------------------------- |
| **Priority**           | Dropdown that sets the priority of the ticket.                           | Diagnostic, Low, Medium, High, Critical                  |
| **Status**             | Dropdown that sets the status of the ticket.                             | Open, Closed                                             |
| **Resolution**         | Text field enabled when status is set to closed.                         | If enabled, this field is required to close a ticket.    |
| **Primary Issue**      | Dropdown list of options to describe primary ticket issue.               | Various options.                                         |
| **Secondary Issue**    | Dropdown list of secondary options to describe ticket issue.             | Options change depending on the Primary Issue selection. |
| **Details**            | Text field for additional information that might be relevant.            | Optional field.                                          |
| **Assign To**          | Dropdown to select user assignment for ticket.                           | Various options.                                         |
| **On Behalf Of**       | Dropdown to select user the ticket is being made for.                    | -                                                        |
| **IM Request**         | Dropdown showing options for IM escalation.                              | IM1, IM2, IM3                                            |
| **Measurement**        | Dropdown showing options for the IM escalation to alert out.             | -                                                        |
| **Well Reported Down** | Checkbox for identify if the well has been reported down.                | -                                                        |
| **EVIN**               | Checkbox marking the VO Ticket to be sent to EVIN in the VOTicket table. | -                                                        |

