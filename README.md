
# hosting an webapp using s3 and Github actions


This project involves hosting a web application using AWS S3 and GitHub Actions. The process can be summarized as follows:

### 1. **Repository Setup:**
   - Create a GitHub repository and add the necessary files for your web application.

### 2. **S3 Bucket Configuration:**
   - Create an S3 bucket on AWS and configure the required policy for hosting the web application.

### 3. **IAM User Setup:**
   - Create an IAM user, attach the S3 policy, and generate an access key and secret access key ID for GitHub Actions integration.

### 4. **GitHub Actions Workflow:**
   - Define a GitHub Actions workflow in the main.yml file, specifying the build and deployment process.

   ![GitHub Actions Workflow](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/a4aa2cd9-410e-449c-931e-6a5f3d3929af)

### 5. **Build and Deployment:**
   - Implement the build and deployment process within the GitHub Actions workflow.

   ![Build and Deployment](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/d60439e1-b4b3-4ac0-a144-18f63ab8fa67)

### 6. **Automatic Upload to S3:**
   - Upon a successful build, GitHub Actions automatically uploads all files to the specified S3 bucket.

   ![Automatic Upload to S3](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/ce66e070-d88e-4b97-8fa2-26366f6d162e)

### 7. **Website Deployment:**
   - The hosted website is now up and running, accessible through the S3 bucket.

   ![Website Deployment](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/281d59b7-0901-4edc-98e8-5ebd42688bc0)

### 8. **Continuous Integration:**
   - When changes are made in the GitHub repository, the GitHub Actions workflow is triggered automatically. It rebuilds and deploys the changes to the website.

   ![Continuous Integration](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/98f71653-f88c-481e-b76f-b3d5a4562159)

### 9. **Updated Website:**
   - The website is updated with modifications made to the GitHub repository files.

   ![Updated Website](https://github.com/sunilkurthakoti/hosting_webapp_s3-githubactions/assets/131526336/dcbbff8d-e31a-47bc-bdbd-aca4b423bfb6)

This streamlined process ensures an automated and efficient web application deployment workflow using AWS S3 and GitHub Actions.
