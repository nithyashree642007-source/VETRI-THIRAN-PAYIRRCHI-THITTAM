# Project Development

The project development was completed in five main tasks:

1. Create UI Policy

Created a UI Policy named “High Impact Control” on the Incident table.

When Impact is High, the Assignment Group becomes mandatory. 



2. Create UI Policy Action

Configured the Urgency field as read-only when Impact is High. 



3. Create onChange Client Script

When Impact changes to High, Urgency is automatically set to High.

An information message is also displayed. 



4. Create onSubmit Client Script

Checks whether Assigned To is empty when Impact is High.

If empty, the Incident cannot be saved and an error message is shown. 



5. Create onCellEdit Client Script

Prevents users from changing State directly through Incident list editing.

State can still be changed through the Incident form.
