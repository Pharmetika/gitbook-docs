# Request to Compound Tasks

When a prescription is filled in the Pharmetika dispense system (ION), ElectricLab automatically generates this task for the lab if there is not enough available inventory to dispense. Additionally, when a formula’s available inventory falls below its inventory reorder point, a **Request to Compound** task is generated.

<figure><img src="../.gitbook/assets/image (65).png" alt="" width="563"><figcaption></figcaption></figure>

As part of this task, the Anticipatory Compounding Limit is provided based on recent dispensing history.

* **Merge if possible:** Checking this enables ElectricLab to search the task queue for additional create lot tasks for the same formula that have been previously created, but not yet started, and merge the tasks to be completed as one task.
  * **Example:** a Create Lot task for testosterone 5% cream (90 gm) is in the task queue and another lot of testosterone 5% cream (30 gm) is needed. The system will merge these tasks into a single task for testosterone 5% cream (120 gm).

While the task is open, ingredient inventory data is visible to ensure that you have adequate ingredient stock prior to scheduling the **Lot Create** task.

To complete the task, click the **Create Task** button to open the **Schedule Task to Create Lot** window.

<figure><img src="../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

Then, click the **Create Task & Mark Complete** button. The system now generates a Lot Create task for a technician to compound.

<figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

