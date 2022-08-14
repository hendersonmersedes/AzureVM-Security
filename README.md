# AzureVM-Security
<p>Azure VM Security</p>
<p>I am still learning all the ins and outs of security so I started playing around in Azure again and discovered a great amount of resources that can be used to defend resources. I also wanted to learn more about how I can break into those resources so I created a few VMs to get me started.</p>
<ol>
   <li> Logging into the Azure portal (portal.azure.com)</li>
   <li> Create a new resource group</li>
   <li> Go to Virtual Machines and Create a Windows 2016 VM</li>
   <li> I kept the port RDP 3389 open. (I cannot stress this enough...<b>SAVE YOUR LOGIN INFORMATION</b>)</li>
   <li> Created a storage account to gather diagnostics information. (This will be used to attach Sentinel later)</li>
   <li> Once validation is passed, click create and wait for the resource to be added</li>
   <li> Now that your VM is created, RDP into it with your log information</li>
   <li> Go back to the Azure portal and search for Sentinel</li>
   <li> Create a new workspace in Sentinel. Activate Sentinel in the workspace</li>
   <li> Connect Microsoft Defender for Cloud </li>
 </ol>
