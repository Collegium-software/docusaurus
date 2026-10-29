---
sidebar_position: 9
sidebar_label: Managing Invoices
---

# Invoices

As a member of the project management team, invoices that are submitted for work completed will need to be reviewed, approved, and paid. Part of the Collegium methodology is to get vendors paid promptly. To aid with this, the platform automatically links invoices with bids and work packages, speeding up the process considerably.

## The invoices tab

As invoices are processed, they appear here.

![Invoice table owner view](/img/invoicesDate.png)

This can easily be filtered by date, by either selecting a month from the dropdown, or selecting a start and end date.

The **Filter** tool gives you the ability to filter on other fields.

**Export** will save out a CSV file of the table contents or print just the table.

The search bar lets you search by typed keywords.

**Export PDF** will save out a PDF of the table contents along with all the submitted invoice documents for the selection.

For each row of the table, if you click on the **Eye** icon, you will download and view the invoice document that the vendor submitted.

The table rows themselves condense a lot of information into an easily digestible table. At a glance you can see who submitted this invoice, what the work package name, vendor name, and PO number is, a summary of the payment status, the results of automated tests that we run, and the status of the invoice.

![Invoice Actions](/img/invoiceActions.png)

Clicking the three dot actions icon gives you more functionality.

**View Bid** will let you review the bid associated with the invoice.

**View Work Package** will let you review the work package associated with the bid and invoice.

This is also where the review process happens.

## The Invoice Processing Process

This is a tiered approach, where the Project Management Team (PMT) and Senior Management Team (SMT) work together. These three roles can be three or more people, or can be held by a single person. They are set in the [Project Wizard](./2edit-a-project.md).

### Initial Review

After confirming that the invoice was submitted correctly and is associated with the correct bid and work, a **PMT** member can click **Mark reviewed**. This indicates that the invoice has passed an initial completeness check and is ready for the Quantity Surveyor (QS) to evaluate.
If it does not meet the required standards, or it is a duplicate, or has some other issue, the **PMT** member can click **Reject Invoice**, and type in a brief reason why. This will instantly update the database, and let the vendor know what has happened.
If the invoice was marked reviewed in error, the user can simply click **Rescind review**.

### Quantity Surveyor Approval

![Actions for a reviewed invoice](/img/invoiceActions2.png)

After review, and after the QS has reviewed the completed work to their satisfaction, a **SMT** member can click **Approve Invoice** clearing the invoice for payment.

If this is done in error, the user can also click **Rescind Approval** to go back to **Reviewed** status.

If the QS has an issue with the invoice, the user can click **Reject Invoice** and type a short message saying why.

### Payment

![Actions for an approved invoice](/img/invoiceActions3.png)

Once payment has been made on an approved invoice, a **SMT** member can click **Mark as Paid**, and the database will be updated accordingly.

The **SMT** member can also click **Rescind Paid** if this was done in error.
