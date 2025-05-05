🔹 GCP (Google Cloud Platform):
A cloud service by Google that lets you run applications, store data, and use powerful computing resources online.

🔹 Google Cloud Platform:
Same as GCP — it includes tools for computing, databases, AI, and storage, all accessible through the internet.

🔹 Project:
In GCP, a project is like a container where you manage all your cloud resources like VMs, databases, and permissions.

🔹 Terraform:
An open-source tool used to automatically create and manage cloud resources (like GCP projects) using simple code.
Access:
Access controls who can view, use, or manage resources in a Google Cloud project. It’s managed through IAM permissions.

🔹 Primitive Role:
Basic roles like Viewer, Editor, and Owner that apply broad access across all resources in a project.

🔹 Predefined Role:
Roles created by Google with specific permissions for a particular service (e.g., Storage Admin, Compute Viewer).

🔹 Custom Role:
User-created roles that allow you to define a set of permissions tailored to your specific needs.

☁️ Google Cloud Platform (GCP) Overview

🔹 Project

A project in GCP is a logical container for resources (like APIs, storage, databases).

All billing, access control, and API usage are tied to a specific project.

🔐 Access Control in GCP

🔹 IAM (Identity and Access Management)

Manages who can do what on which resources.

Roles:

Primitive roles: Basic access (Owner, Editor, Viewer).

Predefined roles: Granular, service-specific roles (e.g., BigQuery Data Viewer, Dialogflow Admin).

Custom roles: You define specific permissions for custom needs.

Service Account:

A special Google account used by apps or VMs to call GCP services.

Attach to APIs, run services like Cloud Run, or authenticate with Dialogflow.

🔌 API Services and Usage

🔹 Billing Based on Usage

GCP APIs and services charge based on actual use:

E.g., number of queries, storage used, compute time, etc.

Each project must be linked to a Billing Account to use paid services.

API Services

API / Service	Purpose:
Dialogflow API	Build conversational agents (chatbots, voicebots) using NLP
Cloud SQL API	Manage relational databases like MySQL/PostgreSQL in the cloud
BigQuery API	Run fast SQL queries on large-scale datasets (data warehouse)
Vertex AI API	Train, deploy, and manage machine learning models
Cloud Run API	Deploy and scale containerized apps with HTTP endpoints automatically
Connectors API	Connect GCP services to external systems (e.g., Salesforce, MySQL, etc)

🔹 Virtual Networking:
Virtual networking in cloud platforms like GCP allows resources (like VMs) to communicate securely using virtual networks.
It includes components like VPCs, subnets, firewalls, and IP addresses to manage traffic flow.

CHAT GPT Versions:
GPT-4.5 is the latest version of ChatGPT, released by OpenAI on February 27, 2025 .
Older versions like GPT-3.5 and GPT-3 were slower and less advanced in understanding and answering questions.

VPC:
🔹 VPC (Virtual Private Cloud) is like your own private network inside the cloud.

🔹 It helps connect and protect your cloud resources like virtual machines, databases, etc.

🔹 You can control:

🔹 Think of it as setting up your own mini data center, but online.

Firewall:
🔹 A firewall is a security system that controls who can access your network and what traffic is allowed in and out.

🔹 It works like a gatekeeper:

It blocks unwanted traffic (like hackers trying to get in).

It allows trusted traffic (like your web browser accessing a website).

🔹 You can set rules to decide which types of data are safe or unsafe.

GCP Storage options:

| **Storage Type**   | **Description**                                                                                                             |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| **Object Storage** | Stores unstructured data as objects (files + metadata). Ideal for backups, images, and logs. Example: Google Cloud Storage. |
| **Block Storage**  | Stores data in fixed-size blocks, like a virtual hard drive. Used for VM disks and databases. Example: Persistent Disk.     |
| **File Storage**   | Provides a traditional folder/file system. Suitable for shared access and legacy applications. Example: Filestore.          |
