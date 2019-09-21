# updating
1. Get CircleCI cli 
```
curl -fLSs https://circle.ci/cli | bash
```
help -> [token](https://circleci.com/docs/2.0/managing-api-tokens/)


1. Edit your orb 

2. Validate it
```
circleci orb validate firebase-deploy.yml 
```

3. Publish
```
circleci orb publish increment firebase-deploy.yml  noyo/firebase-deploy   major|minor|patch
```