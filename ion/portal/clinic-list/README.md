# Clinic List

## Synopsis

The Clinic List page allows for the pharmacy to have a more granular level of control over the clinics that are associated with them.

A **clinic** is the way Pharmetika organizes account groups for practitioners and their staff in the Provider Portal. Clinics usually are a physical location from which the practitioner(s) prescribes.

A practitioner account with the respective permissions assigned to a clinic will also have the ability to view and manage changes to their clinic's details, and invite users to their clinic. They will **not** be able to force users to be associated with their clinic, nor will they be able to grant themselves access to medication templates.

**Note:** [Organizations](../../maintenance/organizations/) are only visible to the pharmacy staff in ION. Organizations are a grouping concept primarily for billing purposes. Clinics and organizations have very different purposes and are not equivalent concepts.

## The Clinic List

<figure><img src="../../.gitbook/assets/image (238).png" alt=""><figcaption></figcaption></figure>

The Clinic List provides a full over-view of all clinics that interact with your pharmacy. From the clinic list, you will be able to [create clinics](./#creating-a-new-clinic), archive clinics, and edit clinics.

If you wish to utilize the Search Clinics feature, you may search for clinics by their clinic name, address, phone number, or fax number.

## Editing a Clinic

To begin editing a clinic, press the blue Edit button in the row of the clinic you desire to edit. The top half of this screen is dedicated to basic details regarding the clinic. When making changes to this general information, you will have to hit the Save button in the bottom right to update it once you are finished.

<div data-full-width="true"><figure><img src="../../.gitbook/assets/image (226).png" alt=""><figcaption><p>An example of what the editing pop-up for clinics looks like.</p></figcaption></figure></div>

### Adding Medication Templates to a Clinic

Under Medication Template Access, you can click the blue + sign to provide clinic template visibility to a specific clinic. You have the ability to add and remove as many templates to a clinic as you wish. To remove a template you have previously added, you can click the red trash button next to the template name. You do not need to re-save the entire clinic to adjust their template access.

To read more about clinic specific template control, you can visit our page on the [Clinic Template Editor](../clinic-template-editor.md).

### Associating Users with a Clinic

The Associate User with Clinic button will allow you to add any existing Provider Portal practitioner and practitioner staff accounts (that your pharmacy has access to) to your target clinic.

To remove a user from a clinic, you can click the red trash button at the end of the row for the corresponding user.

When adding or removing users from a clinic, you do not need to save the entire clinic.

#### A Note on Patient Visibility for Clinic Accounts

Adding or removing users modifies a portal account's visibility and access to the patient data in their patient list.

A patient's visibility status to a provider's account is based on the following factors: has this prescriber prescribed to the patient, did the prescriber create the patient, or is the prescriber in a clinic with another prescriber that has met one of the two previous conditions?

{% hint style="danger" %}
Be very **cautious** when adding or removing users, so that a user's patient visibility is appropriate, and does not violate patient privacy rules.
{% endhint %}

To find out how to view the list of patients a practitioner account has access to, [click here](../practitioners.md#viewing-a-practitioners-patients).

## Creating a New Clinic

If you wish to create a new clinic associated with your pharmacy, you may do so by clicking the blue + New Clinic button in the top right corner of the Clinic List. The New Clinic screen will be nearly identical to the Edit Clinic screen, sans the ability to add users and templates immediately.

The only required field for creating a clinic is it's name. When you have filled out the clinic's basic information, click the blue Save button in the bottom right to save the new clinic.

Once the clinic has been initially created, you can click the [Edit](./#editing-a-clinic) button on it's entry in the Clinic List, then you will be able to associate portal users and templates to it.
