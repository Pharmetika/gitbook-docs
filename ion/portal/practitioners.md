# Practitioners

Overview

The Practitioners page contains a comprehensive list of Provider Portal practitioner accounts. From this screen, the pharmacy can:&#x20;

* See the EPCS status for providers
* Get a list of a practitioner account's patients
* Toggle a practitioner's ability to request EPCS tokens

**Note**: Provider Portal practitioner accounts are not the same as a Prescriber record in ION. For more information on how to manage Prescriber entries, [click here](../maintenance/prescribers/).

## Practitioner List

By default, the Practitioner List is a list of all practitioner Provider Portal accounts that your pharmacy is associated with.

{% hint style="info" %}
On smaller displays, the full width of this table might not fit on your screen. If this is the case, you can scroll the table back and forth horizontally.
{% endhint %}

<figure><img src="../.gitbook/assets/Practitioner List.png" alt=""><figcaption></figcaption></figure>

To automatically begin an email to a practitioner, click the blue letter icon after the name of that practitioner.

The practitioner's primary clinic appears in the **Primary Clinic** column. To see all the clinics to which a practitioner is linked, hover over the blue list icon next to the practitioner's primary clinic.

<figure><img src="../.gitbook/assets/see all clinics for practitioners.png" alt=""><figcaption></figcaption></figure>

Clicking the link button in the Profile column takes you to the [Edit Prescriber](../maintenance/prescribers/) screen for that practitioner.

The Request Token switch, if enabled, allows a practitioner to begin the process of requesting an EPCS token for their account in the Provider Portal. You can toggle the default of this feature for new practitioner accounts in Utilities > System Configuration > System Settings > Provider Portal > Enable EPCS for New Providers by Default.

You can filter the list of practitioner accounts in two ways: with a search field for the practitioner account's username, or with a button group for the practitioner's [EPCS token status](practitioners.md#epcs-statuses).

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

### Viewing a Practitioner's Patients

To view a list of patients a practitioner account may have access to, click the blue **See Patients** text button near the end of the row for a practitioner.

<figure><img src="../.gitbook/assets/image (229).png" alt=""><figcaption><p>A screenshot sample of a provider's patient list.</p></figcaption></figure>

The patient list for the practitioner has the potential to be quite long, depending upon how many patients they have access to. You can see, at a glance, the quantity of accessible patients via the number displayed after the search bar. You will be able to search for a specific patient that the practitioner account may have access to by their name or date of birth.

Clicking the blue link on the patient's name will take you to the [patient's summary](../patient/ion-sms-functionality/patient-profile.md) page.

### EPCS Statuses

When a practitioner account initiates the process for receiving an EPCS token, you will be able to know what stage of the process they are in based on the **EPCS Status** column. The Last Updated column shows the most recent update, and you can use the date range filter to narrow your view.

There are three possible EPCS statuses a practitioner account can be in:

**ID Check** - The practitioner has begun the process of proving their identity. This means their identity has not yet been confirmed.

**Processing** - This stage comes after identity proofing the completion of identity proofing. This means that Pharmetika is working on provisioning the provider's EPCS token.

**Shipped** - Pharmetika has completed token provisioning, and has created a shipping label for shipping the EPCS token to the practitioner's address.

#### Tracking a Shipped Token

When a token for a practitioner has been shipped by Pharmetika, the practitioner's EPCS Status in the Practitioner List will show blue Shipped text with a preceding clipboard icon. By clicking on this text, the tracking number for the token shipment will be copied to your clipboard, in case you need to provide shipping updates to the practitioner.

<div align="center"><figure><img src="../.gitbook/assets/image (214).png" alt=""><figcaption></figcaption></figure></div>
