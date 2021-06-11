---
sidebar_position: 3
---

# Referencing Forms

This feature of the Form Builder allows you to build your forms by importing logic from [component forms](/platform/core-concepts#components). Components are a mechanism for grouping together domain-specific form logic into disparate, reusable bits. You can mix and match components to create forms of arbitrary complexity. Imagine building a form for use in HIV Testing. This form might require the following sections:

- A pre-clinic review section
- A vitals section
- A lab order section
- A lab results section
- An HIV status section
- A Tuberculosis treatment section

It is possible to encapsulate each of the above pieces into a disparate reusable component. You'd then have, say, a Pre-Clinic Review component that handles pre-clinic review concerns. This component would have sections such as:

- A patient's current HIV status
- Whether a visit was scheduled or not
- Reasons for a visit
- The current visit type
- A patient's insurance information
