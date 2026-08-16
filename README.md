#Deployment
 Prepare GitHub Repository
   -Push code: Make sure website is fully commited and pushed to GitHub Repository.
   -Verify entry point: Double check root includes entry file (eg: index.html)

Connect Netlify to GitHub
   -sign up or log in to your Netlify Dashboard.
   -click the 'Add new site' button located on your main dashboard.
   -Select 'Import an existing project' from the optios menu.
   -Choose 'GitHub' under the continuous deployment Git providers list.
   -Authorize Netlify to access your GitHub repositories when prompted by the pop-up window.

Configure Settings and Deploy
   -Select your specific repository from the authorized list.
   -Fill out 'Build settings' if a frontend framework is in use:
       *In this case for static HTML/CSS/Javascript websites: Leave the build command and
        publish directory fields blank.
   -Click the 'Deploy site' button at the bottom of page.

Access Live Site
   -Wait for Netlify to assemble project.
   -click the live link that is automatically generated 'netlfiy.app' to view project.
   -Every new commit pushed in chosen GitHub branch in repository will automatically update
    to personal Netlify website.

GitHub Repository Link: https://github.com/TiffanyAgosto-Martinez/portfolio-website.git

Netlify Link: https://chipper-mermaid-c9f530.netlify.app