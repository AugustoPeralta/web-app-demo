This repo is configured to trigger pipelines in AWS CodePipelines to deploy a static web page in S3 buckets automatically.
The dev branch deploys the code in a dev environment:
        Dev URL:      http://dev.webapp.augustodemos.com/
        
Once the changes are tested in the Dev environment they have to be merged to Main, this automatically triggers the pipeline to deploy in the production environment:
        Prod URL:     http://prod.webapp.augustodemos.com/
