# GitHub Actions - The Complete Guide By Academind

Practices done in the GitHub Actions - The Complete Guide https://www.udemy.com/course/github-actions-the-complete-guide/

## Practices
### Section 3
  
Create 2 workflows in the practice project:
1. One workflow that runs the lint, test and build scripts.
2. One workflow that outputs event details on issues.

### Section 4

Modify the de deploy workflow to be triggered when any one of the following condition is met:
1. Push events in the main branch.
2. Pull Requests targeting the main branch.
3. Enable the manual run button.

### Section 5

Update the deploy workflow to to met the following requirements:
1. Add a new job to build the application and upload the artifacts to the workflow build artifacts space.
2. Download the artifacts in the deploy job and print out the content of the current directory.
3. Use jobs ouputs to get the JS file name from the artifact produced in the build job and print out that value in the deploy job.
4. Use cache for dependencies.
