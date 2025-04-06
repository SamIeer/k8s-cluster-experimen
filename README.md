<h1>Kubernetes Cluster Experiment</h1>
<h3>Overview</h3>
<p>This repository demonstrates a basic Kubernetes cluster setup using Rancher Desktop to explore cluster architecture concepts:<br>
  worker nodes, master nodes, pods, deployments, and autoscaling.<br>
  where Kubernetes will orchestrate a traffic prediction model.</p>

<h3>Purpose</h3>
<p>The goal is to gain hands-on experience with Kubernetes by:<br>
Setting up a local cluster with a master node and worker nodes.<br>
Deploying a simple pod and a multi-replica deployment.<br>
Experimenting with autoscaling based on resource usage.</p>
<p>This experiment provides foundational knowledge for deploying containerized AI models in a distributed edge-core-cloud environment.</p>

<h3>Repository Contents</h3>
<p> <i>pod.yaml:</i> Defines a single Nginx pod.<br>
<i>deployment.yaml:</i> Configures a 3-replica Nginx deployment with resource limits.</p>

<h3>Setup Instructions</h3>
<h4>Prerequisites</h4>
<p><b>Rancher Desktop:</b> Installed and running (download from <a href=rancherdesktop.io).<br>
<b>kubectl:</b> Configured to interact with the Rancher Desktop cluster (included with Rancher Desktop).
Steps</p>
<h3>Start Rancher Desktop:</h3>
<p>Open Rancher Desktop and enable Kubernetes in the settings. This creates a local cluster with a master node and worker nodes.</p>


![Screenshot 2025-04-06 204028](https://github.com/user-attachments/assets/cb19fe40-a040-4a1a-bbe9-ffafbf3a0eff)




![Screenshot 2025-04-06 204009](https://github.com/user-attachments/assets/1db4fbf0-41b5-4c01-a221-2e9010b7e70a)




![Screenshot 2025-04-06 204053](https://github.com/user-attachments/assets/a778f75a-e3d9-4e6c-899e-e0ee866aa6bc)




![Screenshot 2025-04-06 205317](https://github.com/user-attachments/assets/23303c83-71da-4a7a-8830-99a55dc35fb4)



