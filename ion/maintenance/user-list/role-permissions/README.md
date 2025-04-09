# Role Permissions

New and existing users can enable or disable user permissions.

## User Types

{% hint style="info" %}
**Note: Once a user has been created, the user type cannot be changed. Ensure that the pharmacy chooses the appropriate user type when creating a new user.**

If the user type is no longer appropriate for the existing user, the pharmacy can update the user in either of the following ways:

* The pharmacy deactivates the current user and creates a new user with the appropriate updated user type.
* The pharmacy keeps the current user profile and updates the user permissions to the appropriate permissions for that user. &#x20;
{% endhint %}

* **Technician:** A user with a pharmacy technician or technician trainee license. Authorized to process prescriptions in ION.
* **Pharmacist:** A user with a pharmacist license. Authorized to process prescriptions in ION.
* **Customer Support:**  A user who does not hold a pharmacy license of any type. For example, this type might include a logistics employee whose only role is to create shipments, and does not have a pharmacy license to process prescriptions in ION.  This type might also include a sales representative who does not hold a pharmacy license of any type and is unable to process prescriptions in ION.
* **Lab Pharmacist:** A user with a pharmacist license. Their role is to compound in ElectricLab.
* **Lab Technician:** A user with a pharmacy technician or technician trainee license. Their role is to compound in ElectricLab.
* **Handoff:** An internal user type used on tablets to allow patients to sign for the receipt of medications.
* **Point-of-Sale:** An internal user type used on tablets for patient handoff and payments.
* **Interface:** An internal user type for API integrations. Does not apply to most users.
* **Service:** An internal user type to create credentials for API integrations. Does not apply to most users.

## Default Permissions

Default permissions are added for the various user types. It is up to the pharmacy to modify the permissions for the users beyond the default permissions. The table below lists user permissions that are set by default for all existing and new users.

### Organization Permissions

| Role                            | Default Permission     |
| ------------------------------- | ---------------------- |
| Create Organizations            | Technician, Pharmacist |
| Modify Existing Organizations   | Technician, Pharmacist |
| Modify Organization Price Plans | Technician, Pharmacist |

### Prescriber Permissions

| Role                                     | Default Permission     |
| ---------------------------------------- | ---------------------- |
| Create Prescriber Profiles               | Technician, Pharmacist |
| Modify Prescriber Profile                | Technician, Pharmacist |
| Invite Prescriber to Practitioner Portal | Technician, Pharmacist |

### Shipping Permissions

| Role                  | Default Permissions                      |
| --------------------- | ---------------------------------------- |
| Create Shipping Label | Technician, Pharmacist, Customer Support |
| Void Shipping Label   | Technician, Pharmacist, Customer Support |

### Product Permissions

| Role                                             | Default Permissions    |
| ------------------------------------------------ | ---------------------- |
| Add Commercial Product Inventory                 | Technician, Pharmacist |
| Adjust Quantity for Commercial Product Inventory | Technician, Pharmacist |
| Create or Modify Products                        | Technician, Pharmacist |

### Fill Permissions

| Role                                   | Default Permissions                      |
| -------------------------------------- | ---------------------------------------- |
| Fill Prescriptions                     | Technician, Pharmacist                   |
| Modify a Prescription Fill             | Technician, Pharmacist                   |
| Modify Handoff Method on Existing Fill | Technician, Pharmacist, Customer Support |
| Record a Dispense on Prescription Fill | Technician, Pharmacist                   |

### Price Plan Permissions

| Role               | Default Permissions    |
| ------------------ | ---------------------- |
| Create Price Plans | Technician, Pharmacist |
| Modify Price Plans | Technician, Pharmacist |

### User Management Permissions

| Role                      | Default Permissions                     |
| ------------------------- | --------------------------------------- |
| Create New User           | Technician, Pharmacist, Lab Pharmacist  |
| Modify Existing Users     | Technician, Pharmacist, Lab Pharmacist  |
| Set User Role Permissions | Pharmacist, Lab Pharmacist              |

### Configuration Permissions

| Role                                 | Default Permissions                                     |
| ------------------------------------ | ------------------------------------------------------- |
| Modify All System Settings           | Technician, Pharmacist, Lab Technician, Lab Pharmacist  |
| Create Handoff Methods               | Technician, Pharmacist                                  |
| <p></p><p>Modify Handoff Methods</p> | Technician, Pharmacist                                  |
| Modify Sig Code List                 | Technician, Pharmacist                                  |

### Payment Permissions

| Role                      | Default Permissions    |
| ------------------------- | ---------------------- |
| Void Payment Transactions | Technician, Pharmacist |

### Lab Permissions

| Role                                      | Default Permission             |
| ----------------------------------------- | ------------------------------ |
| Print Unit Dose Label                     | Lab Technician, Lab Pharmacist |
| <p>Release Lot from Quarantine</p><p></p> | Lab Technician, Lab Pharmacist |
| Create or Modify Formulas                 | Lab Technician, Lab Pharmacist |
| Modify Lab Configuration                  | Lab Pharmacist                 |
| Modify Lab Ingredients                    | Lab Pharmacist                 |
| Modify Lab Inventory                      | Lab Pharmacist                 |
| Modify Formula Types                      | Lab Pharmacist                 |

