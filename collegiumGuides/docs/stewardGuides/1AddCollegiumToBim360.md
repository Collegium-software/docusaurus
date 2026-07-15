---
sidebar_position: 1
sidebar_label: Add Collegium to Autodesk
---

# Autodesk Integration

In order for Collegium to do its magic, and treat the Building Information Model (BIM) as a database for procurement, we need to allow the Collegium app access to your architectural projects in the Autodesk ecosystem. Lets follow along.

## Step 0: Get access to Autodesk Forma

This is outside your hands, but you as a steward need to be added to the clients Autodesk account so you can set up access to the models from the Collegium app.

## Step 1: Log into Autodesk Forma

Log into Autodesk Forma, then click on **Hub Admin**

![Project Description](/img/autodesk1.png)

Then click on **Custom Integration**

![Project Description](/img/autodesk2.png)

## Step 2: Options & Units

The second page of the Project Wizard. Here you can:

- **Select a Steward:** Pick from a list of active stewards.
- **Bid Format Options:** Lump sum or Unit Rate. Default is Unit Rate, and it's strongly encouraged that we keep it that way.
- **Make Project Private:** Private or not?
- **Make Project Bidding Public:** The whole point of a project is to tender the work required to build it. This sets the default for the Work Package Wizard. Do you want it to be closed, invite-only bidding, or open to anyone.
- **Net Land Area:** How much physical land does the project occupy?
- **Gross Site Area:** How much land are you actually going to use?
- **Net Site Area:** How much land will actually be occupied?
- **Gross Building Area:** Calculated field. The gross construction area + the below ground construction area.
- **GCA/GFA:** Gross Construction Area/Gross Floor Area. Two phrases for the same thing. What is the total amount of floor in the building?
- **Net Floor Area:** Net floor area, Gross Floor Area - walls etc.
- **BGCA:** Below Ground Construction Area. Total floor area below ground. Basements, parking, etc.
- **Floor Area Ratio:** Calculated Field. Gross Floor Area / Gross Site Area.
- **Net Rentable Area:** How much area is actually available to rent?
- **Percent Efficiency:** Calculated Field. Net Rentable Area/Gross Floor Area \* 100.
- **Units:** Metric or imperial.
- **Number of Stories:** How tall is the building?
- **Number of Suites:** How many rental units or individual condos in the project.

![Project Options & Units](/img/projectWizzard2.png)

## Step 3: Location & Uploads

Basic Address details. The platform uses the address to generate latitude and longitude, so enter a real, complete address.

Project will have overview documentation that vendors will want to see before bidding. This is one place to upload it. Either drag the document onto the upload icon, or click in the box and navigate to the file/s you want to upload via the file explorer.

![Project Location & Uploads](/img/projectWizzard3.png)

## Step 4: Team Onboarding

Here we add people who will have roles managing the project. Each "type" of person will have different access to different features on the platform. Start at the top and work down, adding relevant people.

The process is the same for each type (Owner Corp, Prime Consultant, etc.) Select a company from the company dropdown, then select the user from the next dropdown. The user list is limited to those who belong the selected company. The owner corp is also allowed to select a representative. You can then add anyone else that needs access from each company.

To add additional corporations, click **Add Company** then select a different company and representative.

![Project Team Onboarding](/img/projectWizzard4.png)

## Step 5: User Permissions

The final step is to assign roles to the users selected in the previous step. There are several roles available, Senior Management Team (SMT), Project Management Team (PMT), Project Implementation team (PIT), Quantity Surveyor (QS), and View Only. You can select more than one role per user. Small teams may need many roles per user. So give everyone an appropriate role, and when you're done, click **Update Project**. The changes will be saved in the database.

![Project User Permissions](/img/projectWizzard5.png)
