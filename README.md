# SWYNEX Technologies – Final Cloud Deployment Case Study

## Project: CloudSpace – Static Website Deployment

**Internship:** Cloud Computing Internship  
**Company:** SWYNEX Technologies  
**Intern:** Shrivalli Yallapu  
**Internship Duration:** 30 Days  
**Cloud Hosting Platform:** GitHub Pages  
**Project Type:** Static Website Hosting

**Live Website:**  
https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/

**Original Source Repository:**  
https://github.com/naagashrivalliyallapu-ai/cloud-internship-deployment

---

## 1. Introduction

Cloud computing provides on-demand access to computing, storage, networking, and hosting services over the internet.

As part of the SWYNEX Technologies Cloud Computing Internship, I completed a practical project called CloudSpace. The project involved designing a basic cloud architecture, developing and deploying a static website, understanding deployment monitoring, and preparing cost and security checklists.

The website was hosted using GitHub Pages, which allows static websites to be published directly from a GitHub repository.

## 2. Project Objective

The main objectives were:

- Understand the basic components of cloud architecture.
- Design a simple architecture for a web application.
- Develop a static website using HTML and CSS.
- Host the website using GitHub Pages.
- Verify deployment using GitHub Actions.
- Understand basic monitoring and deployment logs.
- Identify cost-management and security practices.
- Document the complete deployment process and lessons learned.

## 3. Cloud Architecture Design

The CloudSpace project uses a simple static website hosting architecture.

### Architecture Components

**1. Client Layer**
- Users access the website through a web browser.
- Requests are sent over HTTPS.

**2. Networking Layer**
- The website is accessed through its GitHub Pages URL.
- HTTPS provides encrypted communication between the browser and the hosting service.

**3. Hosting Layer**
- GitHub Pages hosts and serves the static website files.
- HTML provides the website structure.
- CSS provides the design and styling.

**4. Storage Layer**
- GitHub repository stores the website source files, including `index.html` and `style.css`.

**5. Deployment Layer**
- GitHub Actions runs the Pages build and deployment workflow.
- The deployment workflow publishes the website from the configured repository branch.

**6. Security and Access Control**
- HTTPS is enabled for the public website.
- GitHub repository permissions control who can modify the source files.
- Sensitive information should not be committed to the public repository.

### Architecture Flow

User Browser → HTTPS → GitHub Pages Hosting → Static Website Files

GitHub Repository → GitHub Actions → Build and Deployment → GitHub Pages

## 4. Architecture Diagram

The architecture follows this basic flow:

1. A user opens the CloudSpace website using a browser.
2. The browser sends an HTTPS request to the GitHub Pages hosting service.
3. GitHub Pages serves the website's static HTML and CSS files.
4. The source files are maintained in the GitHub repository.
5. GitHub Actions manages the build and deployment workflow.
6. The deployment status and logs can be checked through the Actions tab.

## 5. Technologies Used

| Technology | Purpose |
|---|---|
| HTML | Website structure |
| CSS | Website styling |
| GitHub | Source code repository |
| GitHub Pages | Static website hosting |
| GitHub Actions | Deployment workflow |
| HTTPS | Secure website access |
| Web Browser | Website testing |

## 6. Website Development and Deployment

The following steps were completed:

1. Created a static website named CloudSpace.
2. Developed the website using HTML and CSS.
3. Created a public GitHub repository.
4. Uploaded the website source files to the repository.
5. Opened repository Settings.
6. Navigated to GitHub Pages.
7. Selected the `main` branch as the publishing source.
8. Configured the root folder for publishing.
9. Enabled GitHub Pages deployment.
10. Verified the deployment through GitHub Actions.
11. Opened the published website and confirmed that it worked correctly.

**Live Deployment URL:**

https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/

## 7. Monitoring and Status Checks

Basic monitoring practices were identified for the deployed website.

**Website availability**
- Open the live website periodically.
- Verify that the homepage loads correctly.
- Check that content and styling appear as expected.

**Deployment monitoring**
- Open the GitHub repository's Actions tab.
- Select the `pages build and deployment` workflow.
- Check the latest workflow status.
- Inspect logs if a deployment fails.

**Alert approach**

GitHub Actions failure notifications can be enabled through GitHub notification settings. If a deployment fails, the notification can help identify the problem. The workflow logs can then be inspected and the source files corrected before another deployment.

A periodic manual website availability check is also useful.

## 8. Cost Awareness

The following practices help avoid unnecessary hosting costs:

- Use GitHub Pages for static website hosting.
- Avoid unnecessary virtual machines and cloud servers.
- Avoid enabling unused paid services.
- Keep website files within GitHub Pages usage limits.
- Review GitHub plan and Actions usage limits.
- Check third-party service charges before enabling them.

GitHub Pages supports public repositories on GitHub Free, subject to its published usage limits. This project does not require a separately provisioned server.

## 9. Security and Access Control

The following security practices were considered:

- Use HTTPS for secure website access.
- Protect GitHub account credentials.
- Enable two-factor authentication.
- Review repository access permissions.
- Avoid uploading passwords, API keys, or access tokens.
- Do not store confidential information in a public repository.
- Review workflow permissions and repository settings periodically.

The CloudSpace website uses the default GitHub Pages HTTPS-enabled domain.

## 10. Testing and Verification

The project was tested using the following checks:

- Opened the live website URL in a browser.
- Verified that the website homepage loaded correctly.
- Checked the website styling and content.
- Checked GitHub Pages publishing settings.
- Verified that the GitHub Actions deployment workflow completed successfully.
- Confirmed that the website was publicly accessible.

**Result:** The CloudSpace website was successfully deployed and verified.

## 11. Challenges and Learning

During this project, I gained practical experience with:

- Understanding how static websites are hosted in the cloud.
- Creating and managing GitHub repositories.
- Configuring GitHub Pages.
- Understanding deployment workflow status.
- Reading GitHub Actions logs.
- Understanding HTTPS and repository access control.
- Recognizing the importance of cost awareness and monitoring.

One important learning was that a successful deployment should also be monitored and protected through appropriate security practices.

## 12. Future Improvements

The project could be improved by:

- Adding automated website availability monitoring.
- Configuring additional alerting for website downtime.
- Improving website responsiveness for mobile devices.
- Adding more pages and interactive features.
- Reviewing security and access permissions regularly.

## 13. Conclusion

The CloudSpace project provided practical exposure to cloud architecture, static website hosting, deployment workflows, monitoring, cost awareness, and security.

By using GitHub Pages and GitHub Actions, I successfully published a static website and learned how to verify its deployment status.

This internship task helped strengthen my foundational knowledge of cloud computing and gave me practical experience in deploying and maintaining a cloud-hosted website.

**Final Project Status: Successfully Deployed and Verified.**

**Live Website:**  
https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/
