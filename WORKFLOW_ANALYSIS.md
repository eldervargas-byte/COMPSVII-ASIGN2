## WorkFlow_Analysis Question 

- What triggers this workflow to run? (Look at the on: section)
When the code is pushed to the main branch

- What are the four main steps this workflow performs? (List each step name)
Step 1: Get the code from the repository
Step 2: Validate HTML files
Step 3: Check for broken links
Step 4: Upload the built site for deployment

- What does the "Checkout code" step do and why is it necessary?
Is there to validate html files, and check links because it must confirm everything accurate to upload for deployment.

- What is the purpose of the environment configuration?
To deploy the environment to GitHub Pages

- How does this automated deployment improve reliability compared to manual deployment?
Compared to manual deployment is less risky and rely for deployment to the Github Pages

- What would happen if you pushed code to a different branch (not main)?
Either its won't work or have an error since the overflow is only trigger when is pushed to main branch
