1. Commit and push to github repo
2. CircleCi Building Phase
   - Spin up environment
   - Preparing environment variables
   - Install Node.js 14.15
   - Checkout Code
   - Install Front-End dependencies
   - Install API dependencies
   - Front-End Lint
   - Front-End Build
   - API Build
3. CircleCi Approval Phase
   - Authorized approval to proceed to deployment phase
4. CircleCi Deployment Phase
   - Spin up environment
   - Preparing environment variables
   - Install Node.js 14.15
   - Setting up Elasatic Beanstalk CLI
   - Install AWS CLI - latest
   - Configure AWS Access Key ID
   - Checkout Code
   - Deploy FrontEnd App
   - Deploy BackEnd App
