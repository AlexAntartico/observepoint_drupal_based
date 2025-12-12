# Reports

This document provides sequential steps and instructions for using the Reports dashboard and creating alerts.

1. Open the Reports dashboard
   - In the application, open the Reports section.
   - The left pane contains navigation options. Select the option labeled "Report runs".
   - Screenshot:
     <img width="1920" height="1080" alt="reports-recentauditsruns" src="https://github.com/user-attachments/assets/cdcc7edc-846b-40c6-86ea-02da3e370584" />

2. View the list of report runs
   - A list of report runs appears.
   - Use the list to find the run you want to inspect.
   - Screenshot:
     <img width="1920" height="1080" alt="reports-recentauditsruns-detail" src="https://github.com/user-attachments/assets/0e3ec09b-c899-4bdd-8200-b395b5c4f4dc" />

3. Open a report run dashboard
   - Select a report run from the list to open its dashboard.
   - The dashboard displays data and controls related to the selected run.
   - Screenshot:
     <img width="1920" height="1080" alt="viewpagesdetail" src="https://github.com/user-attachments/assets/494b4fdb-4155-45ed-a218-ff552eedf911" />

4. Apply a page filter
   - Click the Filters control.
   - Choose Pages.
   - Enter one or more page URLs, path patterns, or identifiers.
   - Click Apply or Confirm to apply the filter.
   - Screenshot:
     <img width="1912" height="651" alt="reports-filter-pages" src="https://github.com/user-attachments/assets/e0083a36-c3d0-4aa4-8da9-322e5da7b824" />

5. Apply a tag filter
   - Click the Filters control.
   - Choose Tags.
   - Select one or more tags from the list or enter tag identifiers.
   - Click Apply or Confirm to apply the filter.
   - Screenshot:
     <img width="1919" height="711" alt="reports-filters-tags" src="https://github.com/user-attachments/assets/e1ba7e07-54e1-4685-a1c0-a822b51ee220" />

6. Inspect an item and create an alert
   - Move the pointer over an item in the report list to view its description.
   - To create an alert based on that item, click the Create alert control associated with the item.
   - Screenshot (hover and create alert):
     <img width="1923" height="710" alt="reports-create-alerts" src="https://github.com/user-attachments/assets/e0fcc79d-1930-434c-b435-9368d6328a40" />

7. Configure alert settings
   - Open the alert configuration menu.
   - Set alert logic:
     - Choose the metric to evaluate.
     - Select an operator (for example, equals, greater than, less than).
     - Enter a threshold value.
     - Define the scope (for example, page-level, tag-level, or run-level).
   - Add filters to narrow alert scope, if needed (pages, tags, other dimensions).
   - Screenshot (alert menu):
     <img width="1902" height="786" alt="reports-createalert2" src="https://github.com/user-attachments/assets/9e74c3c6-0d04-40e0-9fe3-7b51ebaa655a" />
   - Screenshot (alert logic setup):
     <img width="1920" height="1080" alt="reports-alertlogic" src="https://github.com/user-attachments/assets/4e7e02ad-3732-4b16-8e3e-f29dda1a93df" />

8. Set notification recipients and message
   - Enter email addresses for recipients. Separate multiple addresses with commas or use the interface control to add addresses.
   - Enter the notification subject and body message.
   - Optionally include run-specific placeholders or variables supported by the system.
   - Screenshot (email and message setup):
     <img width="1920" height="1080" alt="alert-notification-setup" src="https://github.com/user-attachments/assets/470e14d0-8957-4eff-b50e-bf9ed427275f" />

9. Select a DataSource
   - Choose the DataSource that the alert will use for evaluation.
   - DataSource: ObservePoint term for the method used to collect and analyze data from digital assets. See the ObservePoint documentation for definitions and options:
     https://help.observepoint.com/en/articles/9089312-data-sources-standards-and-configurations
   - Screenshot (select DataSource):
     <img width="1920" height="1080" alt="alerts-datasource" src="https://github.com/user-attachments/assets/fd371a2f-45d9-4219-a1b8-84d869eac9af" />

10. Preview alert results
    - Use the preview control to run the alert logic against prior runs and view which items would have triggered the alert.
    - Review the preview output for accuracy.
    - Adjust logic, filters, or recipients as needed.
    - Screenshot (alerts preview):
      <img width="1920" height="1080" alt="alerts-preview" src="https://github.com/user-attachments/assets/ff759be2-06d6-4497-b482-f53fd2ae1da7" />

11. Save and activate the alert
    - Click Save or Create to store the alert configuration.
    - Confirm activation settings such as schedule or frequency.
    - Test the alert by running a simulated evaluation or waiting for the next scheduled run.

Notes and tips
- When entering filters, verify that filter values match the format used by the reporting system (full URL, path, or tag identifier).
- When composing notification messages, include context fields (run ID, page URL, tag) to help recipients locate the issue.
- Use the preview step to validate logic before activating an alert.
