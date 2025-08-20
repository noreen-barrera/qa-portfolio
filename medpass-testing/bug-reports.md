# Bug Reports – MedPass Laravel Project

This document contains manually reported bugs while testing the MedPass Medical Clearance Status Management System.  
Most recent bugs are listed first.

---

### Status Legend

- 🔴 **Open** – Bug is still unresolved
- 🟢 **Fixed** – Bug has been resolved and confirmed
- ⚪️ **In Progress** – Currently being worked on
- 🟣 **Retest Needed** – Claimed fixed but needs QA confirmation
- 🔵 **Deferred** – Known issue, fix postponed

---
## BUG-003: 
- **Status:** 🔴 Open
- **Date Reported:** June 9, 2025
- **Component:** Add Patient → Assign Test Set Tab
- **Description:** After adding patient, tab does not switch automatically or autofill patient info
- **Steps to Reproduce:**
  1. Add new patient via Add Patient form
  2. Submit the form
- **Expected Result:** System should automatically switch to Assign Test Set tab and preselect new patient
- **Actual Result:** Remained on Add Patient tab, no autofill
- **Severity:** Medium

## BUG-002: 
- **Status:** 🟢 Fixed
- **Date Reported:** June 8, 2025
- **Component:** Assign Test Set
- **Description:** Admin users appearing in patient dropdown search
- **Steps to Reproduce:**
  1. Go to Assign Test Set tab
  2. Open patient search dropdown
- **Expected Result:** Only patients should appear in dropdown
- **Actual Result:** Admin accounts also appeared in dropdown
- **Severity:** Medium

## BUG-001: 
- **Status:** 🟢 Fixed
- **Date Reported:** May 9, 2025
- **Component:** Admin Dashboard Layout
- **Description:** Admin first name not displayed correctly in dropdown
- **Steps to Reproduce:**
  1. Login as admin with first name set to "Rin"
  2. View dropdown on top-right corner
- **Expected Result:** Dropdown should display "Rin" (admin’s first name)
- **Actual Result:** Dropdown displayed only "admin"
- **Severity:** Low
