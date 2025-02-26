# Halting Prescription Processing

This feature enables pharmacies to halt prescription processing based on specific conditions tied to a provider, an organization, or both—each operating independently. Once the options are selected and a reason is entered, a halt message will appear on the **Prescription Entry** page, the **Fill Screen**, or both. The message(s) will serve as a notification, displaying the entered reason. Pharmacies can configure the halt and enter the reason for either page, with the messages appearing on the corresponding page(s)

When this option is enabled for an organization, the halt message(s) will display for all prescribers within that organization. If additional reasons for the halt are needed for a specific provider, the pharmacy must enter those separately for that provider.

## Key Features:

* **Dual Message Display**: Halt messages may appear on one or both pages, depending on the selected options.
* **Reason for Halt**: Pharmacies can specify a reason for the halt when entering the details on the relevant page.
* **Impact on Workflows**:
  * **Prescription Entry**: Users will be unable to proceed beyond data entry on the Prescription Entry page while a halt is active.
  * **Fill Screen**: Pharmacy users will be unable to fill prescriptions when halted.

## Workflow:

1. **Setting a Halt**:
   1.  Navigate to either the provider's profile or Organization profile page and enter the halt reason for the provider, organization, or both.

       <figure><img src="../../../.gitbook/assets/Screenshot 2025-01-15 at 4.27.41 PM.png" alt=""><figcaption><p>Provider profile page</p></figcaption></figure>
   2.

       <figure><img src="../../../.gitbook/assets/Screenshot 2025-01-15 at 4.26.58 PM.png" alt=""><figcaption><p>Organization profile page</p></figcaption></figure>
2.  **Displaying Messages**:

    <figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Provider and Organization halt messages on Prescription Entry page</p></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Provider and Organization halt messages on Prescription Entry page</p></figcaption></figure>

    <figure><img src="../../../.gitbook/assets/Screenshot 2025-01-15 at 4.14.35 PM.png" alt=""><figcaption><p>Provider and Organization halt messages on Fill screen.</p></figcaption></figure>
3. **Disabling Actions**:
   1. The halt will disable the ability to proceed from the prescription entry page.
   2. It will also prevent the filling of existing prescriptions until the halt is removed.
4. **Removing the Halt**:
   1. The halt cannot be overridden; it must be disabled to process the prescription accordingly.
