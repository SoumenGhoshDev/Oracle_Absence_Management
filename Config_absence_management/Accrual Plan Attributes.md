**Accrual Plan Attributes -- Revision Notes**

**1. Introduction**

This topic explains how **Accrual Plans** are defined and configured in
**Oracle Absence Management**.

**Key Questions Covered**

-   What is an **Absence Plan**?

-   What are the **types of Absence Plans**?

-   What is an **Accrual Plan**?

-   How do we **configure an Accrual Plan**?

**2. Absence Plan**

**Definition**

An **Absence Plan** defines the rules governing an employee's
entitlement to **time off from work**.

It determines:

-   Eligibility for leave

-   Leave accrual rules

-   Payment during absence

-   Maximum allowed leave

-   Carryover rules

-   Deduction during absence

-   Termination handling

**Key Capabilities**

Absence plans control:

  -----------------------------------------------------------------------
  **Capability**   **Description**
  ---------------- ------------------------------------------------------
  Eligibility      Determines who can enroll in the plan

  Accrual          How employees earn leave

  Ceiling          Maximum leave balance allowed

  Carryover        Leave that moves to next term

  Deduction        Leave deducted when absence occurs

  Payment          Pay calculation during absence
  -----------------------------------------------------------------------

**When Absence Plans Are Required**

Absence Plans are required when:

-   There is a **payroll impact**

-   Leave balances must be **tracked in the system**

Absence Plans are **NOT required** when:

-   You only want to **track time off**

-   No balance management is needed

**3. Types of Absence Plans**

There are **6 major types of absence plans**.

**1. Accrual Plans**

Employees **earn leave periodically** over time.

**Examples**

-   Vacation leave

-   Annual leave

**Characteristics**

-   Leave accumulates over time

-   Based on predefined rules

-   Maintains balance

**2. Qualification Plans**

Leave is granted due to **specific events**.

**Examples**

-   Sick leave

-   Maternity leave

-   Family leave

-   Military leave

-   Jury duty

Employees **qualify for leave due to a situation**, not due to
accumulation.

**3. No Entitlement Plans**

Used when:

-   No accrual exists

-   No entitlement exists

**Example**

-   Leave Without Pay

-   Disciplinary suspension

Used only to **track absence time**.

**4. Agreement Plans**

Used for **shared parental leave programs** required by government
regulations.

**Example**

A mother may convert:

-   Remaining maternity leave\
    → into

-   Shared parental leave for partner

These leaves can be **used intermittently within a defined period**.

**5. Compensatory Plans**

Tracks **compensatory time off**.

**Concept**

Instead of overtime payment, employees receive **paid time off**.

Example:

Employee works extra hours → gets **compensatory leave**

**6. Donation Plans**

Employees can **donate leave balances**.

**Donation Types**

1.  Donate to another employee

2.  Donate to a **shared leave pool**

Used for employees who need additional leave due to:

-   Medical emergencies

-   Personal crises

**4. Accrual Plans (Detailed)**

**Definition**

An **Accrual Plan** allows employees to **earn paid leave
periodically**.

**Example**

-   Vacation leave

-   Paid annual leave

**Characteristics**

-   Workers are automatically enrolled

-   Leave accrues periodically

-   Balance maintained yearly

-   Absences reduce balance

**Other Balance Impacts**

Balances may also change due to:

-   Adjustments

-   Transfers

-   Disbursements

-   Donations

**5. Rules Required to Configure an Accrual Plan**

When configuring an accrual plan, the following rules must be defined.

**5.1 Accrual Term**

The **Accrual Term** defines the time period during which leave
accumulates.

**Common Term Types**

  -----------------------------------------------------------------------
  **Term Type**              **Description**
  -------------------------- --------------------------------------------
  Calendar Year              Jan 1 → Dec 31

  Anniversary Year           Based on employee hire date
  -----------------------------------------------------------------------

**Example**

Employee hire date: **May 1**

Accrual term:

May 1 → April 30

Then resets next year.

**5.2 Plan Eligibility**

Determines **who can enroll in the plan**.

Configured using:

**Eligibility Profiles**

Eligibility can depend on:

-   Job

-   Location

-   Department

-   Worker type

**5.3 Enrollment and Termination Rules**

Controls:

-   When employees are enrolled

-   What happens when they leave

Rules include:

-   Negative balance handling

-   Positive balance handling

-   Plan termination conditions

**5.4 Transfer, Rollover, and Carryover**

Defines what happens to **remaining leave balances**.

**Options**

-   Transfer balance to new plan

-   Carry forward to next year

-   Expire unused leave

**5.5 Prior Balance Reinstatement**

When an employee:

-   Terminates

-   Loses eligibility

The system may **retain their balance**.

If the employee is rehired:

The balance can be **reinstated**.

**5.6 Vesting Period**

A **vesting period** restricts leave usage.

Employees may:

-   Accrue leave

-   But **cannot use it immediately**

Example:

Employee accrues leave but must wait **90 days before using it**.

**5.7 Plan Limits**

Defines the **maximum leave balance** allowed.

Example:

Maximum leave = **30 days**

Even if accrual generates more leave, balance **cannot exceed this
limit**.

**5.8 Balance Adjustments**

HR specialists can adjust balances manually.

**Types of Adjustments**

-   Balance corrections

-   Transfer between plans

-   Other manual adjustments

-   Elective disbursements

**5.9 Payments**

Defines how leave balances interact with **payroll**.

Payment rules may apply when:

-   Workers are paid during absence

-   Leave balance is cashed out

-   Liability cost must be calculated

-   Employees exit the company

**5.10 Disbursement**

Employees may **convert leave to cash**.

Configuration defines:

-   Eligibility

-   Who can initiate request

-   Maximum disbursement hours

**5.11 Donation**

Defines whether employees can **donate leave**.

Configuration includes:

-   Eligibility to donate

-   Who can initiate donation

-   Donation limits

**6. Steps to Create an Accrual Plan**

Navigate to:

My Client Groups\
→ Absences\
→ Absence Plans

Then click:

Create

**7. Accrual Plan Configuration Tabs**

While creating a plan, several tabs must be configured.

**7.1 Plan Attributes Tab**

Defines the **basic details of the plan**.

**Key Fields**

  -----------------------------------------------------------------------
  **Field**          **Description**
  ------------------ ----------------------------------------------------
  Plan Name          Name of the absence plan

  Unit of Measure    Days, Hours, Weeks

  Accrual Term       Period during which leave accrues

  Balance Visibility Whether employees/managers can view balances
  -----------------------------------------------------------------------

**Unit of Measure Options**

Leave can be measured in:

-   Days

-   Hours

-   Weeks

-   Months

-   Years

-   Calendar Days

**Important Note**

Work schedules calculate absence duration **only if the unit is**:

-   Days

-   Hours

**Hours Display Configuration**

If **Hours** is selected:

System can display balances in:

Hours : Minutes

Example:

8:30

**Alternative Schedule Category**

Allows the system to use a **non-primary work schedule** for absence
calculation.

Useful when:

Employees work multiple schedules.

**Processing Level**

Currently:

Plans process against **all active assignments** in the work
relationship.

**Conversion Formula**

Used when leave must be converted to another unit.

**Examples**

  -----------------------------------------------------------------------
  **Scenario**             **Conversion**
  ------------------------ ----------------------------------------------
  FMLA leave               Days → Weeks

  UK Sick Pay              Days → Qualifying Days
  -----------------------------------------------------------------------

**8. Plan Term Types**

**Calendar Year**

Accrual period starts on a specific calendar date.

Example:

Start: January 1\
End: December 31

Resets every year.

**Anniversary Year**

Based on employee **hire date**.

Example:

Hire Date = May 1

Accrual Period:

May 1 → April 30

Resets each anniversary.

**9. Flexfields**

Two types of flexfields exist in the configuration.

**Legislative Information**

Used to capture **country-specific legal information**.

Example:

-   US regulations

-   UK statutory rules

**Descriptive Flexfields**

Used to capture **custom additional information** about the absence
plan.

Defined by the organization.

**10. Example Configuration**

Example Vacation Accrual Plan Setup:

  -----------------------------------------------------------------------
  **Field**                            **Value**
  ------------------------------------ ----------------------------------
  Plan Name                            Vacation Accrual Plan

  Unit of Measure                      Days

  Legislative Data Group               US

  Plan Term                            Calendar Year

  Renewal Date                         April 1

  Balance Visibility                   Worker & Manager
  -----------------------------------------------------------------------

**11. Key Takeaways**

**Important Concepts**

-   An **Absence Plan** controls employee time-off rules.

-   There are **6 types of absence plans**.

-   **Accrual Plans** allow employees to earn leave periodically.

-   Leave balances are affected by:

    -   Accrual

    -   Absence

    -   Adjustments

    -   Transfers

    -   Donations

**Important Configuration Areas**

When creating an accrual plan, define:

1.  Accrual term

2.  Eligibility

3.  Enrollment rules

4.  Balance limits

5.  Carryover rules

6.  Payment rules

7.  Disbursement rules

8.  Donation rules

✅ **Recommended Practice**

Create a **Vacation Accrual Plan** in the system and configure:

-   Plan Attributes

-   Participation

-   Accrual Rules

-   Entries and Balances

This helps understand the **real system configuration**.
