# INTRODUCTION:
Our project is “Implement Client Script and UI Policy in ServiceNow Incident Management.”

The main purpose of this project is to improve the accuracy and consistency of Incident records in ServiceNow. When users create or update incidents, they may sometimes enter incomplete or incorrect information.

To solve this problem, we have used UI Policies and Client Scripts to dynamically control fields, make important fields mandatory, automatically set values, and validate information before an incident is saved.

In our project, when the Impact is set to High, the Assignment Group becomes mandatory and Urgency is automatically set to High. We also prevent an incident from being saved when the required Assigned To information is missing. Additionally, we restrict users from changing the State directly through list editing.

This project demonstrates how ServiceNow can use UI Policies, Client Scripts, and GlideForm APIs to create a more controlled and reliable Incident Management process.
