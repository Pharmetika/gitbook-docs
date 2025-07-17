# Requesting a Signature at Pickup

You can require patients to sign for prescriptions using a separate device when they pick them up, which is especially useful for controlled substances in states that require a signature from the patient.

## Set Up the Device

First, you need to configure the tablet or other device you plan to use to collect patient signatures. Signatures can be collected using any internet-connected device, including a computer.

1. In ION, [create a new user](../../maintenance/user-list/add-new-user.md) with a type of Handoff in the **Type** field. In the **Email** field, make sure to enter an email that is accessible to staff so the user's login credentials can easily be retrieved if forgotten. To create a new user, you need to have the Create New User permission enabled. For more information about updating permissions, refer to the [Modifying Permissions](../../maintenance/user-list/role-permissions/modifying-permissions.md) page.
2. On the device you're using to collect signatures, log in as the handoff user you created in the previous step.

## Request a Patient's Signature at Pickup

To request a signature for a specific prescription, first make sure the prescription appears in the **Prescription Hand-off** queue. If it doesn't yet appear in the **Scan Out List** section of the queue, scan the prescription transaction ID into the **Scan Prescription Into Ready Queue** field.

<figure><img src="../../.gitbook/assets/Scan Prescription Into Ready Queue.png" alt="The Scan Prescriptions Into Ready Queue field is highlighted in the Prescription Hand-off queue."><figcaption></figcaption></figure>

Click the **Request Signature** button (1). If the button doesn't appear, find the prescription in the **Ready** section (2) below the **Scan Prescription Into Ready Queue** field, select the checkbox (3) next to the prescription, and click the blue right arrow (4) to move it into the **Complete** section (5).

<figure><img src="../../.gitbook/assets/How to get the Request Signature button.png" alt=""><figcaption></figcaption></figure>

In the **Request Signature** window, fill out the fields and click **Request Signature**. If identity verification is required, you can also enter that information here.

<figure><img src="../../.gitbook/assets/Request Signature window.png" alt=""><figcaption></figcaption></figure>

## Collect the Signature

1. After a pharmacy user clicks the **Request Signature** button in the **Request Signature** window as described above, the prescription appears in the **Prescription List** section on the device you configured earlier. Remember, you must log into the device using the handoff user you created earlier.
2. Ask the patient to review the information on the device. If the information is correct, they can click the gray **Mark All Confirmed** button.

<figure><img src="../../.gitbook/assets/Mark All Confirmed.png" alt=""><figcaption></figcaption></figure>

3. To open the signature window, the patient can click the green **Sign for prescriptions** button.

<figure><img src="../../.gitbook/assets/Sign for Prescriptions.png" alt=""><figcaption></figcaption></figure>

4. After the patient signs in the signature window, they can click the **Accept & Submit** button to complete the process.

<figure><img src="../../.gitbook/assets/Signature pad.png" alt=""><figcaption></figcaption></figure>

After the signature is saved, pharmacy users can see that the patient signed for the prescription at pickup in the **Fill History** window. If the prescription has an associated signature, a signature icon appears.&#x20;

<figure><img src="../../.gitbook/assets/Signature icon.png" alt=""><figcaption></figcaption></figure>

Click this icon to see the signature and details about its collection.

<figure><img src="../../.gitbook/assets/Signature info.png" alt=""><figcaption></figcaption></figure>
