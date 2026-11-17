## What Triggers Workflow to run?
In the .yml file pushes and pull requests to the main branch causes the workflow to run

## Four Main Steps Workflow performs
1. Getting code from the repository
2. Validating HTML files
3. Checks for broken links in the files
4. Upload built site for deployment

## What checkout code step does and why it is necessary 
actions/checkout@v4 Downloads the code from the repository for a "runner", which is a temporary VM in GitHub's cloud. This is so Actions can automatically run tests, compile code into applications, and or deploy the app to hosting providers (AWS, Azure, Vercel, or GitHub Pages). 

## Purpose of enviornment configuration

To set the URL of the page and configure GitHub Pages, and allows the code to run smoothly across different setups. 

## How Automated deployment improves reliability

Less room for human error. Forces deployment steps to be followed. Tests are run on before every deployment. Tests are ran in a standarized enviornment.

## What would happen if I pushed code to a different branch?
THE GITHUB ACTIONS YAML FILE WOULD NOT DO ANYTHING SINCE THE CODE ONLY RUNS ON PUSHES TO THE MAIN BRANCH.