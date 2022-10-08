<h2>F5 Distributed Cloud Customer Sites (Cloud or Edge) App Stack</h2>

<h3>Edge Application Platform</h3>

![image](images/001ce.png)<br>
<a id="toc"></a>
<br>
<h3>Table of Contents</h3>
<a href="#pre">PRE-REQUISITE<a><br>
<a href="#apc">SECTION 1: Prepare App Stack CE Sites</a><br>
<a href="#dap">SECTION 2: Deploy the sample Frontend and Backend apps to the App Stack at Customer Sites</a><br>
<a href="#cap">SECTION 3: Connect Backend App to Frontend App</a><br>
<a href="#cwp">SECTION 4: Configure WAAP</a><br>
<a href="#k8s">SECTION 5: Quick Comparison on generic Kubernetes Deployment vs XC vK8s (App Stack)</a><br>
<a href="#ack">ACKNOWLEDGEMENT</a><br>
<br>
<h4><a id="pre">PRE-REQUISITE</a></h4>
•	F5 Distributed Cloud credential<br>
•	Laptop/desktop browser with internet connectivity<br>
•	Two VMs, either on public cloud or on-premise (VMware/KVM)<br>
<br>
<a href="#toc">Table of Content</a>
<a id="acc"></a><br>
<h4>SECTION 1: Prepare App Stack CE Sites</a></h4>
This section focusses on setting up customer sites (Cloud or Edge) VMs<br><br>
1.1) Login to XC account at https://console.ves.volterra.io/ (Lab tenant will be provided)<br>
<br> 
1.2) Prepare 2x CE sites in VMware/KVM/Public Cloud (min 4vCPU, 16GB, 64GB storage), totally isolated network environment like VPC/vNET or can be in the same subnet for on-premise.<br>
<br>
1.3) Navigate to:<br>

![image](images/002ceandedge.png)<br>

1.4) Create/Retrieve your Site Token: Manage > Site Management > Site Tokens<br>
![image](images/003sitetokens.png)<br>

1.5) Create K8s Cluster (Keep the Name consistent and the same for K8s Cluster, App Stack, and the CE Cluster Name of the App Stack)<br>
![image](images/004k8scluster.png)
![image](images/005addk8s.png)
![image](images/006createk8s.png)<br>

<h4>SECTION 2: Deploy the sample frontend and backend apps to the App Stack at Customer Sites</a></h4>
This section focusses on deploying sample applications into customer sites (Cloud or Edge) running App Stack<br><br>

<h4>SECTION 3: Connect Backend App to Frontend App</a></h4>
This section focusses on connecting sample applications (Frontend and Backend on customer sites (Cloud or Edge) running App Stack<br><br>

<h4>SECTION 4: Configure WAAP</a></h4>
This section focusses on setting up Wab Application and API Protection (WAAP)<br><br>

<h4>SECTION 5: Quick Comparison on generic Kubernetes Deployment vs F5XC Managed K8s/vK8s (App Stack)</a></h4>
This section focusses on comparing generic Kubernetes Deployment and F5XC Kubernetes<br><br>

<a href="#toc">Table of Content</a>
<a id="ack"></a>
<br>
<h4>Acknowledgement</h4>
1)	Klark Ooi, Channel Partnership - APCJ, F5, Lab Author<br>
<br>
Please provide your feedback about this Lab session at following URL, thank you!<br>
<br>
https://forms.office.com/r/js15ACgWwH<br>
<br>
Next labs, Bot Protection, automated (scripted) provision, and more<br>
Look forward to seeing you again at next lab.<br>
<br>


