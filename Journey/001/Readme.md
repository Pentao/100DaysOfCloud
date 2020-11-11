**Add a cover photo like:**
![Screenshot](banners/Day-001-RBAC.png)
# Managing Role-Based Access Control on Azure
## Introduction

✍️ RBAC allows the segregation of duties within the organization.

- Team A in charge of managing VMs
- Team B in charge of managing costs
- Team C in charge of security

Role assignments can be assigned at the management group level up to the resource.

Elements od a Role Assignment

- Security Principal: a user, group, service principal or managed identity requiring access to Azure Resources.
- Role Definition: List of allowed or denied actions, the 3 most common are:
    - Owner: Full acccess to resources and ca delegate access to others.
    - Contributor: Full access, unable to delegate control. 
    - Reader: Can only view resources in Azure. 
    
        NOTE: The "Global Administrator" role in Azure AD can elevate access to the "User access administrator" role at the root scope (/) in order to Regain access to an Azure subscription or management group when a user has lost access, see more [here](https://docs.microsoft.com/en-us/azure/role-based-access-control/elevate-access-global-admin). 
- Scope: can be applied at the:
    - Management Group level
    - Subscription/Resource Group Level
    - Individual Resources.

RBAC can be viewed, added, or removed, from a blade called "Access Control (IAM).

Notes taken from: [Managing Azure Role-Based Access Control (RBAC) - Azure Training](https://www.youtube.com/watch?v=WBj_zjVHMDw&ab_channel=MicrosoftIgnite)

## Prerequisite

✍️ (What) Explain in one or two sentences the base knowledge a reader would need before describing the the details of the cloud service or topic.

## Use Case

- 🖼️ (Show-Me) Create an graphic or diagram that illustrate the use-case of how this knowledge could be applied to real-world project
- ✍️ (Show-Me) Explain in one or two sentences the use case

## Cloud Research

- ✍️ Document your trial and errors. Share what you tried to learn and understand about the cloud topic or while completing micro-project.
- 🖼️ Show as many screenshot as possible so others can experience in your cloud research.

## Try yourself

✍️ Add a mini tutorial to encourage the reader to get started learning something new about the cloud.

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 1 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

### Step 3 — Summary of Step

![Screenshot](https://via.placeholder.com/500x300)

## ☁️ Cloud Outcome

✍️ (Result) Describe your personal outcome, and lessons learned.

## Next Steps

✍️ Describe what you think you think you want to do next.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[link](link)
