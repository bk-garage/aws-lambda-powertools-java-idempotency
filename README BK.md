# Bulent's notes

Follow the associated workshop:
https://catalog.us-east-1.prod.workshops.aws/workshops/a7011c82-e4af-4a52-80fa-fcd61f1dacd9/en-US


## Deploy the sample application

** Read the original README **

- No need to create an AWS Cloud9 Environment.
- "sam build --use-container" didn't work with Rancher Desktop's Docker. Couldn't mount the source folder.


```bash
sam build
sam deploy --guided
sam deploy # to deploy the changes
```

