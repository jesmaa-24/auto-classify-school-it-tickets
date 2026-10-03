# auto-classify-school-it-tickets
ServiceNow Flow Designer project that automatically classifies school IT tickets based on their short description and updates the appropriate category and subcategory.
# Auto Classify School IT Tickets

## Project Overview
This project uses ServiceNow Flow Designer to automatically classify school IT support tickets.

## Features
- Automatically processes IT tickets
- Checks the ticket short description
- Identifies the ticket type
- Updates the appropriate category and subcategory
- Reduces manual ticket classification

## Technologies Used
- ServiceNow
- Flow Designer
- ServiceNow Tables
- Conditional Logic

## Workflow
1. An IT ticket is created.
2. The flow reads the Short Description.
3. Conditions identify the issue type.
4. The corresponding category/subcategory is updated.
5. The classified ticket is stored in the Incident Workflow table.

## Example
Input:
Network Issue

Output:
Category: Network
Subcategory: Wi-Fi

## Result
The flow was successfully tested in ServiceNow with the condition evaluated as True and the update action completed successfully.
