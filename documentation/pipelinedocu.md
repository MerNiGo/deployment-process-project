# CircleCI Process

![alt text](./pictures/Pipeline_Flow%20.png)

### Build Process

1. Installing node on system
2. Installing the dependencies for the front-end and the back-end
3. Lint the front-end code
4. Run the build script for front-end and back-end

### Approval

After the build steps are successfully done, the pipeline process goes on hold and wait for manual approval.
If the building process failed, the deployment process ends till the building process completed successfully.

### Deployment

1. Installing node on system
2. Installing and setup eb-cli and aws-cli
3. deploy the back-end
    - Installing dependencies
    - Build
    - Set environment variables
    - Deploy with eb-cli
4. Deploy the front-end
    - Installing dependencies
    - Build
    - deploy with aws-cli


