# Re-Billing a Fill

{% hint style="info" %}
The re-bill functionality described here does not apply to insurance claims. If you need to re-bill insurance, you must void the prescription and then fill it a second time, making sure to enter the insurance plan in the **Bill to** field.
{% endhint %}

After a prescription has been filled, the price of a prescription or the party to which it is billed might need to be modified. For example, a technician might have initially billed a prescription to a patient, but then received a request from the clinic to bill the prescription to the organization. To re-bill a patient or organization after a prescription has been filled:

1. Open the Patient Summary activity.
2. In the **Prescription History** section, locate the prescription you want to re-bill.
3. In the **Last Filled** column, click **Fills** to open the **Fill History** window.
4. Click the **Fill Entry** button to open the existing fill.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdA1tExGNRsP8zfZ-Qk-ebm4meW8gfpYYnBZP77dP-LQwwVha_QR5kINVVt-fT772CDf5dxltGh18FIruJdqSMkatD1dsWxYnyFQthCQcqRR9-kISU4p1uRrIE2BNGTnB8J2lt8?key=x-QZ4YtTOhbfyu0Rd25adfkv" alt="The Fill Entry button is highlighted in fill history."><figcaption></figcaption></figure>

1. Update the desired field in the **Pricing** section of the fill. For example, you might change the value in the **Bill to** field.&#x20;
2.

    <figure><img src="../../.gitbook/assets/Pricing section for rebill.png" alt="The Pricing section is shown in the fill."><figcaption></figcaption></figure>
3. Click the **Re-Bill** button.

&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdTUVPxiPlEznHnNC_Dur7zkhH3VwyYYjvJux0w2_YlGrx3QN9IkSnU-3DgoZS0YzvjGM9BZiL_cLuW5v26hrda6lQ78TA4QA4uG3FTY_rSxxD-HBhc0gRUT12JkgkiMC_QVkMPOA?key=x-QZ4YtTOhbfyu0Rd25adfkv" alt="The Re-Bill button is highlighted in an existing fill."><figcaption></figcaption></figure>

If the prescription is successfully re-billed, the **Billing information updated** message appears.

<figure><img src="../../.gitbook/assets/Billing info updated.png" alt=""><figcaption></figcaption></figure>

If the prescription was already paid for at the previous price or by the previous payer, a warning message appears.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd68gqrbvqFpiWbJYEPQWqLFgItQCaW1C96WFbID2SCK8sBh11UT_SbTH6jYLcsK9P4IkRKZjW3AFB0acLl9FXoFEwXQwJUYpnjJaH3YQbloMPw9i-F7v5xeToYOhNGd4JWdoiyrQ?key=x-QZ4YtTOhbfyu0Rd25adfkv" alt="A warning message appears that states, &#x22;This fill has already been paid for. Continue?&#x22;"><figcaption></figcaption></figure>

Click **Cancel** to return to the payments page. Click **OK** to see more details about what actions you need to take to resolve the existing payment.&#x20;

For example, in the image below, the user clicked **Re-Bill** for a medication that was already marked Paid as part of an existing invoice. The user can click the **Invoice will need to be recreated** link to open the Payments page and create a new invoice, or click the **Payment may need to be refunded** link to open the Payments page and process a refund for the medication.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBmoYdaCOtc9lpdlTFFwDgBo9eu7BV-mrtXYKoMc7YRIhIUZJs7M2nVfZyVQmzj1VE2e5Q-kJtZQPGkA-DXyx_o8PyfHfOWCQYrS47lx6UCR6bWeqKJFuDb1P6Xh4hhu6793581w?key=x-QZ4YtTOhbfyu0Rd25adfkv" alt="The following warnings appear in the fill: &#x22;Transaction already in invoice&#x22; and &#x22;Transaction has already been marked paid.&#x22;"><figcaption></figcaption></figure>

After you complete the rebill process, you must manually refund or charge the difference.

{% hint style="info" %}
Any manual entry in the **Unbilled** section for a patient or organization will not be associated with the original paid transaction. Your pharmacy must establish a process for reconciling these manually-entered items.
{% endhint %}

If the fill transaction was initially set to patient pay and paid for by the patient, but requires a change to organization pay, the user manually refunds the patient. Then, the user makes a manual entry in the organization’s **Unbilled** section with any necessary information for reconciliation. You can’t mark an existing paid fill transaction as unpaid.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdCXmFjyqAlwU0a5ZZ1zwt-uf8GOahX7KQOMqWH7My4ay2MveAzVsUATBCL1yriLr9udlzjvhYpT9M64rCmZmkNrgEt-KFcbifUsaKnN7ZUa9PkVdZ6e40ripIg-kaUGYRgtTf4Lg?key=x-QZ4YtTOhbfyu0Rd25adfkv" alt="A manual entry is highlighted in the Unbilled Items section."><figcaption></figcaption></figure>

If the price was modified during the re-bill process, you need to manually charge or refund the difference after rebilling the item. The original fill transaction remains marked as paid.\
