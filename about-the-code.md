# About the Code

This tax calculator is built using the [Ractive.js](http://ractivejs.org) javascript library and the [skeleton responsive theme](http://getskeleton.com/). We wanted a user experience that would allow users to easily input and adjust the calculator parameters (household size, income, medical issues, etc,) so that, in addition to exploring their current Medicaid eligibility, they might also explore how Medicaid might change for them as their circumstances change.

## The code explained

Basically, we are setting up a system where all changes made by the user are being watched. When something changes, the system notices and immediately adjusts the variables that calculate the new Medicaid measures.

Here is a breakdown of what happens when each user-input element is changed and an explanation of the functions used to calculate the new measures.

### Poverty

Poverty status and poverty levels are calculated using the user's household size and income. We used the Department of Health and Human Services (HHS) Poverty Guidelines for 2018 to measure poverty status.

Users making above 138% of the Federal Poverty Level (FPL) do not qualify for Medicaid. 

### Medicare and medical waivers

If you receive Medicare benefits or you have a qualifying medical waiver, nothing changes for you. You keep your same benefits, and are exempt from any changes.


{this page is still being updated...}