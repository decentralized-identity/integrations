# User Stories - Home Addition Story

A homeowner is hiring a contractor with multiple employees to build an addition onto their home. The homeowner needs a Building Permit from the City Building Department and the contractor needs to get a Clearance Letter from the Worker Safety Agency (WSA). At various times, various entities involved (the WSA, the homeowner, the City Building Inspector, the WSA Inspector) need to verify documents held by others in the process. The need for documentation and the verification of those documents are described in the user stories below.

# Story 1 - Acme Registers with Corporate Registry

The CEO of Acme Construction Corporation signs up to get an account for the Corporate Registry (government run).

If the company registration doesn't exist it is created.

The CEO requests a digital copy of Acme's corporate registration. CEO receives the digital copy and another copy is placed in the public record.

## Update Company Information

The CEO of Acme needs to register a "doing business as" name for Acme, which is "Acme Construction" and "AcmeCon".

## Use Cases

* Create Digital Copy of Corporate Registration
* Store Digital Copy of Corporate Registration
* Update (Revoke and Re-Issue) Digital Copy of Corporate Registration

# Story 2 - Acme Obtains WSA Clearance Letter

Acme, a construction corporation, that has registered with the corporate registry. As a local business in good standing, Acme must be able to provide proof to Worker Safety Agency (WSA) of its corporate registration and its compliance with criteria for being up to date with its payroll reporting and insurance payments. A **Clearance Letter** is issued by the WSA to companies in good standing with the WSA. Acme obtains a **Clearance Letter** so that it's employees will be able to provide proof of their  association with a firm in good standing.

## Use Cases

* Acme Applies to WSA for Clearance Letter
* WSA issues a Clearance Letter
* WSA updates a Clearance Letter
* WSA revokes a Clearance Letter
* Acme Updates WSA account information

# Story 3 - # Home Addition Project

A Homeowner has decided to add an extension to her residential home. After completing her financial and architectural dependencies she obtains a Residential Building Permit from the City Building Department. She has also contracted with Acme Construction Company for the project. When the work commences she needs to verifies Acme employees that arrive onsite each day for Acme credentials which include proof of employment as well as Acme's WSA clearance letter.

## Use Cases

* Homeowner Building Permit Application
* Acme requests proof of building permit from Homeowner
* Onsite Acme Employee Validation

# Story 4 - Acme Provides Clearance Letter For Authorized Employees

Acme Construction Corporation needs to provide authorized employees with a copy of the Clearance Letter that it received from the Workplace Safety Agency (WSA).

Acme employees can then present the Clearance Letter to the Homeowner and other interested parties. Updates to Clearance Letter will be shared as well.

## Use Cases

* Store Digital Copy of Clearance Letter
* CRUD Clearance Letter
* Notify Interested Parties of Changes

# Story 5 - City Inspector Performs Site Inspection

City Inspector arrives at home owner's job site to perform inspection. First step is to validate that the required building permit is in place and that the contractors on site are covered by Workplace Safety Agency (WSA) insurance.

City Inspector requests building permit from home owner, receiving a digital copy of the building permit. Inspector requests Contractor's WSA Clearance Letter from Home Owner for Acme and that each job site employee works for Acme. Permit, Clearance Letter, and Employee Badges are proved (as valid).

## Use Cases

* Present permit, clearance letter, and employee badges
* Prove Claim

# Story 6 - Commercial Building Permit Acquisition

The entity owning a new shopping plaza has registered with the corporate registry. The owner of a new shopping plaza has just received financial and architectural approvals for proceeding with the project. He obtains a new Commercial  Building Permit from the City Building Department.

## Use Cases

* Commercial Building Permit Application

# Story 7 Acme Assigns An Employee to the Home Addition Project

Acme is assigning an employee construction worker to the Home Addition Project. As part of the assignment process, Acme provides credentials needed by the employee on the job site:

* their Acme employee badge, and
* If necessary (e.g. foremen) a copy of Acme's Clearance Letter issued by WSA.

*Out of scope of this User Story are the scenarios around the hiring of the employee and the (many) other elements of onboarding that employee outside of the employee's participation in the Home Addition Project.*

## Use Cases

1. New employee gets/has a documentation wallet.
1. Acme issues employee badge
1. Acme issues new employee proof of the Acme Clearance Letter issued by WSA

# Story 8 - Home Owner Verifies Contractor

<To Be Created>

# Story 9 - Contractor Verifies Home Owner

<To Be Created>

# Story 10 - WSA Inspector Performs Site Inspection

<To Be Created>
