# DevOps AZ-204: Project 3

## Project Title
**Azure Policy for Virtual Machine Naming**

## Duration
⏱ Completed in approximately 2–3 hours

## Business Scenario
Skill-up Online explored **Azure Container Service** for deploying a container-based workload.  
As part of this project, I built and ran a container in **Azure Container Instance (ACI)** using a custom or pre-built Docker image.

---

## Completed Steps

1. **Created Resource Group**
   - **Name:** `AZ204-Project3-RG`
   - **Region:** East US

2. **Built Docker Container Image**
   - Used a base image from Docker Hub
   - Verified successful local build.

3. **Created Azure Container Registry (ACR)**
   - Hosted the container image in a secure, private registry.

4. **Pushed Docker Image to ACR**
   - Tagged the image appropriately.
   - Successfully pushed using `docker push`.

5. **Deployed Azure Container Instance (ACI)**
   - Pulled the image from ACR.
   - Configured CPU/memory settings.
   - Assigned a DNS label for public access.

---

## Output / Results
- **Azure Resources Created:**
  - Azure Container Registry
    
  - <img width="685" height="371" alt="image" src="https://github.com/user-attachments/assets/fced96cc-c8d2-422b-83d8-26a37c29ea92" />


  - Azure Container Instance
  - <img width="685" height="371" alt="image" src="https://github.com/user-attachments/assets/fced96cc-c8d2-422b-83d8-26a37c29ea92" />
- **Container Status:** Running and publicly accessible.
- <img width="685" height="371" alt="image" src="https://github.com/user-attachments/assets/fced96cc-c8d2-422b-83d8-26a37c29ea92" />
- **Image Source:** Azure Container Registry.
<img width="685" height="371" alt="image" src="https://github.com/user-attachments/assets/fced96cc-c8d2-422b-83d8-26a37c29ea92" />
- **Verification:** Tested container endpoint successfully.

---


## Key Learnings
- Managing container lifecycle with Azure services.
- Building, tagging, and pushing Docker images to ACR.
- Deploying and managing ACI with Azure CLI.
- Configuring public access via DNS labels.

---
