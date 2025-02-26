# Practitioners

## Synopsis

The Practitioners page contains a comprehensive list of Provider Portal practitioner accounts. From this screen, the pharmacy will be able to see at a glance: visibility of the EPCS status for providers, get a list of a practitioner account's patients, toggle their ability to request EPCS tokens, et cetera.

**Note**: Provider Portal practitioner accounts are not the same as a Prescriber entry in ION. For more information on how to manage Prescriber entries, [click here](../maintenance/prescribers/).

## Practitioner List

The practitioner list, by default, is a list of all practitioner Provider Portal accounts that your pharmacy is associated with.

**FAQ:** On smaller displays, the full width of this table may not fit on your screen. If this is the case, you will be able to scroll the table back and forth horizontally.

<figure><img src="../.gitbook/assets/image (571).png" alt=""><figcaption><p>A sample screenshot of what the practitioner list should look like.</p></figcaption></figure>

The blue mail icon after the name of the practitioner is a button that will automatically begin an email to the practitioner in question.

The Profile column provides a link button, which will take you to the [Edit Prescriber](../maintenance/prescribers/) screen for the practitioner profile in question.

The Request Token switch, if enabled, will allow practitioner accounts to begin the process of requesting an EPCS token for their account in the Provider Portal. You can toggle the default of this feature for new practitioner accounts in Utilities -> System Configuration -> System Settings -> Provider Portal -> Enable EPCS for New Providers by Default.

You are able to filter the list of practitioner accounts in two ways: via a search field for the practitioner account's username, and a button group for the practitioner's [EPCS token status](practitioners.md#epcs-statuses).

<figure><img src="../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

### Viewing a Practitioner's Patients

To view a list of patients a practitioner account may have access to, click the blue See Patients text button near the end of the row for a practitioner.

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
