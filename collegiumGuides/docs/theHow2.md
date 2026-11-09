---
sidebar_position: 2
---

# The How 2

## A Guide to getting started on a Collegium based project

This “How2” introduces model-based project delivery: data from your models feeds the Collegium Platform to support cost certainty, schedule predictability, and faster life-cycle cash flows—requiring you to model at a different level, where the focus is BIM ≠ CAD 2.0, but Information Models = Building Data 1.0, providing digital data for every need in the process of Making Buildings.

Steps below use Revit and are color coded—within typical moderate Revit skills, and what needs slightly more effort but well within most firms' grasp.

1. **ISO 19650 “Compliant” not “Certified”:**
   - a. Obtain and read Parts 1, 2 & 4.
   - b. Set up BIM360 or Forma as your ISO 19650-compliant Common Data Environment.
   - c. Provide access to BIM360 for Collegium Steward.

2. **REVIT:**
   - a. Follow ISO 19650 naming; set up separate, linked discipline RVT files.
   - b. Set up worksets by Discipline, then subdiscipline; e.g. A:ARCH, then A:ARCH-WALLS.
   - c. Project Units = Metric; Collegium handles other unit conversion.
   - d. Add the following Parameters into your template:
     1. Under “Identity Data” add: Masterformat 1, 2, 3 & Other.
     2. Add or move Primary Units to “Identity Data.”
     3. Add or move Quote Units to “Identity Data.”
   - e. Obtain updated Information from Collegium:
     1. Update “Assembly Code” parameter with a new `*.txt` file.
     2. Apply the LOD Matrix and Budget Classification maturity level.
   - f. Your Revit Families:
     1. Use ISO 19650 descriptors.
     2. Describe assemblies via “Construction Assembly” unless modeling each element singly (e.g. exterior walls = “Wall” + “Cladding”).
     3. Use “Generic Models” only when an element cannot be categorized.
     4. Model Geometry to Uniformat Level 4 only.
     5. Reference Performance to Masterformat Level 3 only.
   - g. Publishing:
     1. It is best to create separate “Site” and “Building” models.
     2. Publish models from a default 3D view, scoped to the workset being priced.
     3. Use Revit’s Compare tool to list elements Added, Modified, or Deleted between published model versions.

3. **INDUSTRY STANDARDS:**
   - a. Obtain copies and read:
     1. ASTM E2516 Cost Classifications.
     2. ASTM E1804 Cost Analysis During Design.
     3. ASTM 1557 Standard Classification for Building Elements UNIFORMAT.
     4. BIM Forum, LOD Specification (latest Version).
     5. MASTERFORMAT 2018.

4. **3D and 2D:**
   - a. Model to 3-decimal-mm accuracy; reconcile to nearest 1mm by changing distance, not rounding/overriding.
   - b. Use a Project and Survey Point to locate every model geospatially.
   - c. 2D can't replace the 3D model—it carries no data; use only where data isn't required.

This is intended as an outline—developing your own framework within these guidelines is encouraged.
