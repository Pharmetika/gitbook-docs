# Task Queue

The Task Queue shows focused information for all tasks that are in the queue. Users can refine their view by searching for a provider or patient to locate a specific task. They can also filter tasks by criteria like type, priority, or status. The task queue then shows all tasks matching the selected filters, organized chronologically from oldest to newest.

<figure><img src="../.gitbook/assets/Task Queue new.png" alt="The Task Queue shows six due or overdue tasks with filters set."><figcaption><p>Tasks are color-coded based on priority.</p></figcaption></figure>

Tasks appear highlighted in different colors based on their task priority:

* Red tasks are marked Urgent, and should be worked first.
* Yellow tasks are marked Elevated, and should be worked second, after Urgent tasks are reviewed.
* White tasks are marked Normal and can be worked within regular processing times.

{% hint style="info" %}
Note that task priority and fill priority are different pieces of data with different meanings. Task priority refers to how urgently the task needs to be completed, while fill priority refers to how urgently an existing prescription needs to be filled. These two values don’t need to be identical for each prescription.
{% endhint %}

## Commonly-Used Task Types

Some of the most commonly-used task types are described below.

**New Prescription:** Created for new electronic prescriptions pending data entry. To complete the task, click it and complete data entry for the prescription, then click **Mark e-Rx Task Complete**.

<figure><img src="../.gitbook/assets/Mark e-Rx Task Complete button.png" alt="The Mark e-Rx Task Complete checkbox is highlighted in the Prescription Entry activity."><figcaption></figcaption></figure>

**Incoming Fax:** Created for new faxes either pending review or data entry. Click the task to open the **Incoming Fax** window. Here, you can review or print the fax, create a new prescription entry from the fax, create a new task, and mark this task as completed.

<figure><img src="../.gitbook/assets/Incoming Fax window.png" alt="The Incoming Fax task shows options to create a new prescription entry, create a task, print fax pages, and more."><figcaption></figcaption></figure>

**Enter Prescription:** Created when incoming fax tasks are opened and the user creates a new prescription entry in the Incoming Fax window. Click the task to open Prescription Entry and complete data entry, then complete the task by clicking **Mark Task Complete.**&#x20;

<figure><img src="../.gitbook/assets/Mark Task Complete button.png" alt="The Mark Task Complete button is highlighted in the Prescription Entry activity."><figcaption></figcaption></figure>

**Prescription Entry:** Created when a new prescription has been entered and saved, but has not yet been verified by a pharmacist for data accuracy. To complete the task, click the task to open it and then click **Mark Verified** to verify the prescription.

<figure><img src="../.gitbook/assets/MArk Verified button in task.png" alt="The Mark Verified button is highlighted in the Prescription Entry activity."><figcaption></figcaption></figure>

**New Formulation Request:** Created when a pharmacist selects the **Requires new formula** checkbox in a new prescription. This action also places the prescription in pending status.

New formulation requests require coordination between the dispensing and lab teams. The dispensing team must contact the lab to request the new formula, and the lab must contact the dispensing team when the new formula is complete. After the new formulation is created and the dispensing team is notified, the pharmacist can open the New Formulation Request task and clear the **Requires new formula** checkbox.

<figure><img src="../.gitbook/assets/Requires new formula checkbox.png" alt="The Requires new formula checkbox is highlighted in the Prescription Entry activity."><figcaption></figcaption></figure>

**Prescription Clarification:** Created when a user selects the **Requires clarification** checkbox in a prescription entry. To complete the task after a clarification is received, the user enters the clarification, clicks **Add**, and then clears the **Requires clarification** checkbox.

<figure><img src="../.gitbook/assets/Requires clarification.png" alt="The Requires clarification checkbox is highlighted in the Prescription Entry activity."><figcaption></figcaption></figure>

**Prescription Entry Verification:** Created when a new prescription’s status is set to **Ready for Verification**. To complete the task, click the task to open it and verify the prescription.

<figure><img src="../.gitbook/assets/Ready for Verification.png" alt="The Ready for Verification status appears in the Prescription Entry activity."><figcaption></figcaption></figure>

**Prescription - Newly Created:** Created when a new prescription is verified. From these tasks, users can select the **Schedule patient call** checkbox (1) to create a task that reminds the user to call the patient to review medication history and payment information. They can also select the **Send new prescription message** button (2) to send a new prescription SMS message to the patient. To see this option, the patient must have a phone number documented in the **Demographics** section of the patient profile and must have SMS communication enabled in the **Communication Preferences** section of the patient profile.

To complete this task and schedule the patient call or send the SMS, click the task to open it and click **Mark Complete** (3).

<figure><img src="../.gitbook/assets/Prescription - Newly Created, second version.png" alt="The Schedule patient call checkbox, the Send new prescription message checkbox, and the Mark Complete button are each highlighted in a Prescription - Newly Created task."><figcaption></figcaption></figure>

**Second Refill Authorization Fax:** Created when a refill reauthorization request is submitted to a prescriber. This task reminds users to resend a second reauthorization request to the prescriber’s office if the original request remains unapproved or unreceived. From within the task, the user can click the **Schedule prescriber call if no response** checkbox (1) to create a new Call Prescriber for Refill task, which prompts users to place a call to the prescriber to discuss the refill. The user can also select the **Send ‘second notice'** checkbox (2), which automatically sends a second refill request fax to the prescriber and generates a new Second Refill Authorization Fax task with a new follow-up date.

After the user receives an approval for the request, they can clear the **Schedule patient call** and **Send new prescription message** checkboxes and then complete the task by clicking **Mark Complete** (3).

<figure><img src="../.gitbook/assets/Second Refill Authorization Request.png" alt="The Schedule prescriber call if no response checkbox, the Send second notice checkbox, and the Mark Complete button are all highlighted in a Second Refill Authorization Fax task."><figcaption></figcaption></figure>

**Call Prescriber:** Created when a user clicks the **Add Task** button at the bottom of the **Prescriber Information** window.

<figure><img src="../.gitbook/assets/Prescriber Information window to create task.png" alt="The Add Task button and associated text box are highlighted at the bottom of the Prescriber Information window."><figcaption></figcaption></figure>

The task shows the prescriber’s phone number and the message entered by the user who created the task. To complete the task, click **Mark Complete**.

<figure><img src="../.gitbook/assets/Call Prescriber task.png" alt="The Call Prescriber task shows the same text entered by a user in the Prescriber Information window when the task was created."><figcaption></figcaption></figure>

**Call Patient:** Automatically created when a user selects the **Schedule patient call** checkbox in a **Prescription - Newly Created** task, or manually created in the **Patient Contact** section of the **Patient Summary** activity. If the patient doesn’t answer or the user needs to reschedule the call for another reason, the user can click **Log Task Event** (1) and select the **Reschedule** checkbox. After the patient call is finished, complete the task by clicking **Mark Complete** (2).

<figure><img src="../.gitbook/assets/Call Patient task.png" alt="The Log Task Event button and the Mark Complete button are highlighted in a Call Patient task."><figcaption></figcaption></figure>

**SMS Received:** Created when your pharmacy receives an incoming text message. Click the task to review the text message and respond if needed, then complete the task by clicking **Mark Complete.**

<figure><img src="../.gitbook/assets/SMS received.png" alt="The Mark Complete button is highlighted in an SMS Received task."><figcaption></figcaption></figure>

**Payment Method Update:** Created when a patient adds a new payment method using a web browser site that is sent to them with an [SMS](https://app.gitbook.com/o/SiIjEi2l03RLG9aUYT2g/s/QiiUOZlkw8dQZCIkjwLF/patient/payments/managing-payment-sources/smsing-a-payment-link) or [email](https://app.gitbook.com/o/SiIjEi2l03RLG9aUYT2g/s/QiiUOZlkw8dQZCIkjwLF/patient/payments/managing-payment-sources/emailing-a-payment-link) message. When a user clicks on the task to open it, they can see information about the payment source the patient added and a list of unbilled items for the patient. To complete the task, click **Mark Complete**.\


<figure><img src="../.gitbook/assets/Payment Method Update.png" alt="The Mark Complete button is highlighted in a Payment Method Update task."><figcaption></figcaption></figure>
