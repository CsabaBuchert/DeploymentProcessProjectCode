# Infrastructure
This project use CircleCI. CircleCI automatically build and deploy the project to **S3** bucket(frontend) and to **EB** after a new change appear in connected github repository.

## Workflow steps
- Back-End install dependencies
- Back-End build
- Back-End deploy to EB
- Front-End install dependencies
- Front-End build
- Front-End deploy to S3 bucket
