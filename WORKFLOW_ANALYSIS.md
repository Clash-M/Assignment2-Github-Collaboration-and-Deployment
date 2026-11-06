## What Triggers Workflow to run?
In the .yml file pushes and pull request causes the workflow to run

## Four Main Steps Workflow performs
1. Getting code from the repository
2. Validating HTML files
3. Cheecks for broken links in the files
4. Upload built site for deployment

## What checkout code step does and why it is necessary 
actions/checkout@v4 Downloads the code from the repository, this is necessary to push to the main branch.

## Purpose of enviornment configuration
To set the URL of the page

## How Automated deployment improves reliability

Less room for human error. Forces deployment steps to be followed. Tests are run on before every deployment. Tests are ran in a standarized enviornment.

## What would happen if I pushed code to a different branch?
Nothing would change as long as the file is there in the branch.