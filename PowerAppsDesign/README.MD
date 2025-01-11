# PowerApps Design Details

## App Structure
The app consists of the following screens:
1. **Home Screen**: Displays open cases and a button to create a new case.
2. **Case Details Screen**: Shows detailed information for a selected case.
3. **Case Resolution Screen**: Allows users to resolve or escalate cases.

## Key Controls and Logic
- **Case List Gallery**: Displays a gallery of all open cases from SharePoint.
- **Form Control**: Used for creating or editing cases, bound to the `CaseManagement` SharePoint list.
- **SLA Timer**: A timer control bound to the SLA end date to visually track remaining time.

## Design Steps
1. Create a blank canvas app in PowerApps.
2. Add a connection to the `CaseManagement` SharePoint list.
3. Design the screens using labels, galleries, and forms.
4. Implement formulas to filter, sort, and navigate between screens.
5. Test the app and publish it for users.

