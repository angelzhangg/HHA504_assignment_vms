## Objective
The objective of this assignment is to provide hands-on experience with managing Virtual Machines (VMs) in both Azure and Google Cloud Platform (GCP). You will learn how to start, stop, and monitor the costs associated with running VMs on these cloud platforms.

### 1. Start and Stop a Virtual Machine
- **Azure:**
  - Navigate to the Azure portal and create a new Virtual Machine.
  - Choose a basic configuration (e.g., Ubuntu Server, Standard B1s size).
  - Start the VM and allow it to run for a few minutes.
![vm](https://github.com/user-attachments/assets/c6fa0b0a-7b06-439a-8b4a-af51874161e8)
![vm error](https://github.com/user-attachments/assets/5780f7b8-bd15-45c0-b540-3446506f44db)
> I ran into some issues when running my VM on Azure. The standard configuration(Standard B1s) was not available to me as were many of the other sizes. I can only assume there was some permission issues that were not resolved with my student account. I played around and found that EC96as worked as a size however, when I went to review and create, I was unable to proceed to the next step. Thus, my validation failed.

- **GCP:**
  - Access the Google Cloud Console and create a new VM instance using Compute Engine.
  - Select a basic configuration (e.g., Debian GNU/Linux, e2-micro instance type).
  - Start the VM and let it run for a few minutes.
  - Stop the VM and document the steps you followed.
![gcp vm](https://github.com/user-attachments/assets/5805a05e-352c-46c7-b1cd-2d3d26663ac0)
![gcp vm details](https://github.com/user-attachments/assets/bafa1f8f-728e-4efe-b2d9-bb376253df3f)
![gcp vm details2](https://github.com/user-attachments/assets/48f9d39f-a770-44f9-8800-62a6b624d19c)
> In GCP, I was able to create a VM much easier. I selected the basic configurations and let it run for a few minutes before I stopped the VM.

### 2. Monitor VM Costs
- **Azure:**
  - After starting and stopping the VM, navigate to the Cost Management and Billing section.
  - Find the cost associated with running your VM for the time it was active.
 > I was unable to run the Azure VM from ealier thus, I could not monitor the costs.

- **GCP:**
  - In the GCP Console, go to the Billing section and identify the cost incurred by your VM during its runtime.
![gcp biling](https://github.com/user-attachments/assets/8d26da69-d8bd-414c-aa54-0aa746481f7e)
> In GCP, I navigated to the billing section and under reports, I noticed that no costs was recorded during the time I ran my VM machine. This is probably due to the VM not being able to run for a sufficient amount of time to aquire any costs. However, if the VM ran for a longer period of time, the charges would be viewed under "Cost Breakdown."

### 3. Compare and Reflect
- Compare the costs of running a VM in Azure versus GCP. Consider factors such as the configuration used, the duration for which the VM was active, and any differences in cost visibility between the platforms.
> The costs of running a VM in Azure versus GCP was not identified. There were problems running a VM on Azure and no costs was recorded for GCP. I believe this test was not successful as I was unable to compare the costs.
- Reflect on the ease of starting, stopping, and monitoring VMs on each platform. Which platform did you find more intuitive or user-friendly? Why?
>I believe running the VMs on GCP is more user-friendly only because it was easier to navigate. The platform is more straightforward and the setup is laid out right in front of you. 
