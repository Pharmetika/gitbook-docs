# Integrating with Parata

{% hint style="info" %}
If your organization uses a Parata dispensing machine, Pharmetika has Parata integration available. Please email [education@pharmetika.com](mailto:education@pharmetika.com) for more details.
{% endhint %}

If your organization uses Parata, an automated dispensing system, you can enable ION integration with that system. Here’s how it works:

1. When a technician clicks the **Fill** button on a prescription, the prescription’s information is sent to the Parata machine. While the Parata machine is assessing the data, the prescription appears in the Dispense queue with a status of Filled.
2. If the Parata machine successfully accepts the fill, it is processed by the Parata machine. The prescription is then ready to be checked by the technician. The technician doesn’t need to click **Record and Label**, because this step is performed by the Parata machine.
3. If the Parata machine fails to accept the fill, the prescription remains in the dispense queue with a status of Filled. From there, users have two options:
   1. They can retrigger the dispense within the Parata machine.
   2. They can void the current fill in ION and then fill the prescription again.

You can enable this integration for a specific product by completing the following steps:

1. Go to Maintenance > Product and search for an existing product. If you already know the product name, skip the search.
2. Open the **Product Options** section.
3. Select the **Dispense from Parata** checkbox.

When this checkbox is selected, the system sends data for the product to Parata, including a Pharmetika fill label that you can print from Parata.
