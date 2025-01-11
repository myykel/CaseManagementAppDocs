# Power Automate Workflow Details

## Automation Overview
Power Automate workflows ensure smooth handling of cases by automating key processes.

## Key Workflows
1. **Case Assignment Workflow**:
   - **Trigger**: When a new item is created in the `CaseManagement` SharePoint list.
   - **Actions**:
     - Assign the case to a team member based on predefined rules.
     - Send a notification via Teams to the assigned user.

2. **SLA Expiry Notification**:
   - **Trigger**: When the SLA end time is near (e.g., 1 hour left).
   - **Actions**:
     - Notify the case owner about the approaching SLA deadline.
     - Update the case status in the SharePoint list.

## Steps to Create a Workflow
1. Open Power Automate and select **Create a Flow**.
2. Choose a trigger (e.g., "When an item is created").
3. Add actions, such as sending notifications or updating items.
4. Test the flow with sample data and publish it.

