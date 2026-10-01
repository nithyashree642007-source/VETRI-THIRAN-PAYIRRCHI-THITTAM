# Tools Used

1.ServiceNow Personal Developer Instance (PDI)

2.Incident Table

3.UI Policies

4.UI Policy Actions

5.Client Scripts

6.GlideForm APIs

g_form.setValue()

g_form.addInfoMessage()

g_form.showErrorBox()

callback() 

# Client Script Types Used

**1. onChange Client Script – Automatically sets Urgency to High when Impact changes to High.**

**2. onSubmit Client Script – Prevents saving when Impact is High and Assigned To is empty.**

**3. onCellEdit Client Script – Prevents changing State directly through list editing.**   

# Project Workflow

**Incident Record**

↓

**Check Impact**

↓

**Is Impact = High?**

↓

**UI Policy + Client Script**

↓

**Control Fields / Set Values / Validate Data**

↓

**Valid Incident Record**

