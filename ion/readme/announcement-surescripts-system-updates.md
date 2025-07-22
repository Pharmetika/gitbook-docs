# Announcement: SureScripts System Updates

We are pleased to announce that we have completed our direct SureScripts integration!

Incoming electronic prescriptions will now come to ION directly from SureScripts without another intermediary, which gives us (and you) more visibility into the submission process.

We can also now take advantage of additional NCPDP electronic prescribing transactions, which can help improve your workflow. Here’s what’s new with this integration:\


* _Rx renewal responses_, which are responses to electronic refill requests sent by the pharmacy, are now accepted. These responses create an entry in the **Prescription Entry** queue.
* _Change requests_ are now sent. Change requests are similar to clarification requests while allowing you to request more information from prescribers.

<figure><img src="../.gitbook/assets/Entry details.png" alt=""><figcaption></figcaption></figure>

With these requests, your pharmacy can request important prescriber information, such as a DEA or license number, and include more details.

If the change request is successfully sent, a green confirmation message appears. If the change request is not sent successfully, a red error message appears.

Response messages to these requests are sent to the **Other Messages Queue**.

<figure><img src="../.gitbook/assets/Other Messages queue.png" alt=""><figcaption></figcaption></figure>

Here’s an example of an approved message:

<figure><img src="../.gitbook/assets/image (5) (2).png" alt=""><figcaption></figcaption></figure>

* _Electronic Reauthorization requests_ can now accept a response from a prescriber. These requests are sent from pharmacies to request a prescription refill. Now, users can click the gear icon to request a change or add additional information.

<figure><img src="../.gitbook/assets/Rx history.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Advanced Electronic Re-Auth.png" alt=""><figcaption></figcaption></figure>

* _Cancel Rx requests_ are now accepted. These requests are received when a provider sends a message to cancel a medication or prescription. If a prescription number is associated with the request, it appears in the request message. These requests are sent to the **Other Messages Queue**.

After you receive a Cancel Rx request, you can submit an approved or denied response back to the prescriber with an optional note. If the response is a denial, you can also include a denial reason.&#x20;

<figure><img src="../.gitbook/assets/Rx cancel request - denial.png" alt=""><figcaption></figcaption></figure>

If there is a prescription number associated with the Cancel Rx request, you can discontinue the prescription from the request by clicking the red circle next to the prescription number.

<figure><img src="../.gitbook/assets/Cancel rx from request.png" alt="A red circle is highlighted next to a prescription number, and a warning message states, &#x22;Are you sure you want to discontinue this Rx?&#x22;"><figcaption></figcaption></figure>

If there is no prescription associated with the Cancel Rx request, manually submit a response back to the prescriber and then manually locate the medication order in the **Prescription Entry Queue** and discontinue it.

* _Rx Fill notifications_ are now accepted. These messages allow a prescriber to receive a notification of a prescription fill after the prescription leaves the pharmacy.
* _Rx Transfer transactions_ are not available, because they do not support compounds.\
