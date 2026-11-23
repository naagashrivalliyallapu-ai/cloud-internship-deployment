# Task 3: Monitoring and Cost Awareness

## Project: CloudSpace – Static Website Deployment

**Internship Domain:** Cloud Computing
**Company:** SWYNEX Technologies
**Hosting Platform:** GitHub Pages
**Repository:** [https://github.com/naagashrivalliyallapu-ai/cloud-internship-deployment](https://github.com/naagashrivalliyallapu-ai/cloud-internship-deployment)
**Live Website:** [https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/](https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/)

## 1. Introduction

Monitoring and cost awareness are important parts of cloud computing. Monitoring helps verify that an application is available and that deployment processes are successful. Cost awareness helps avoid unnecessary expenses, while security practices protect the project and its resources.

This task explains basic monitoring, a simple alert approach, and cost and security checks for the CloudSpace website hosted on GitHub Pages.

## 2. Monitoring and Status Checks

The CloudSpace website is monitored using the following basic checks:

**A. Website availability check**

- Open the live website URL in a browser.
- Verify that the homepage loads correctly.
- Check that the website content, styling, and navigation display properly.
- Repeat the check periodically to confirm that the website remains accessible.

**B. GitHub Pages deployment status**

- Open the GitHub repository.
- Navigate to the Actions tab.
- Select the `pages build and deployment` workflow.
- Check whether the latest deployment shows a successful status.
- If a deployment fails, open the workflow run and inspect the job logs to identify the error.

**C. Deployment logs**
GitHub Actions provides logs for each workflow run. These logs help identify whether the deployment completed successfully or failed during a particular step.

For this project, the successful deployment status and the live website URL were verified.

## 3. Simple Alert Idea

A simple alert approach is to enable GitHub Actions failure notifications.

**Proposed alert process:**

1. Enable email or web notifications for relevant GitHub Actions workflow failures in GitHub notification settings.
2. Monitor the `pages build and deployment` workflow.
3. If a deployment fails, check the notification and open the workflow logs.
4. Identify the failed step, correct the issue, and trigger a new deployment by committing the corrected files.

An additional manual availability check can be performed periodically by opening the live website.

**Expected result:** The project owner can identify deployment failures and respond to website availability issues quickly.

## 4. Cost Awareness Checklist

The following checks help avoid unnecessary hosting expenses:

- [x] Use GitHub Pages for static website hosting.
- [x] Avoid provisioning unnecessary cloud servers or virtual machines.
- [x] Avoid unused paid hosting services and add-ons.
- [x] Keep website files and images within GitHub Pages usage limits.
- [x] Review GitHub plan and Actions usage limits periodically.
- [ ] Review any third-party services before enabling paid features.

GitHub Pages is available for public repositories on GitHub Free. It avoids the need to maintain a separate web server for this static website. Usage limits still apply, so the project should remain within GitHub's published quotas.

## 5. Security and Access-Control Checklist

- [x] Use HTTPS for secure website access.
- [x] Keep the repository visibility and public website visibility in mind.
- [x] Do not upload passwords, API keys, access tokens, or other secrets.
- [x] Do not store personal or confidential information in the public repository.
- [x] Review repository access and permissions.
- [ ] Enable two-factor authentication on the GitHub account.
- [ ] Give collaborators only the permissions they require.
- [ ] Review repository settings and workflow permissions periodically.

The GitHub Pages website uses the default HTTPS-enabled `github.io` domain. Since the repository and website are publicly accessible, sensitive information must never be committed to the project.

## 6. Result

Basic monitoring and status-check procedures were identified for the CloudSpace website. GitHub Actions deployment logs can be used to review deployment results, while periodic browser checks help verify website availability.

A simple failure-notification approach was proposed. Cost and security checklists were also prepared to support responsible hosting and access management.

## 7. Conclusion

This task provided an understanding of basic cloud monitoring, deployment status checks, alert planning, cost awareness, and security practices. These practices help maintain a reliable and secure static website while avoiding unnecessary hosting expenses.

**Project Status:** Successfully deployed and publicly accessible.

**Live Website:** [https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/](https://naagashrivalliyallapu-ai.github.io/cloud-internship-deployment/)

