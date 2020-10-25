# papershare

Download artifact:
```
curl --output main.pdf --location --header "PRIVATE-TOKEN: <token>" "https://gitlab.informatik.uni-bremen.de/api/v4/projects/bsimon%2Fk-servers-predictions/jobs/artifacts/master/raw/main.pdf?job=build"
```

List project jobs: 
```
curl --location --header "PRIVATE-TOKEN: <token>" "https://gitlab.informatik.uni-bremen.de/api/v4/projects/bsimon%2Fk-servers-predictions/jobs?scope=success"
```

Download artifacts of a job.
```
curl --output artifacts.zip --header "PRIVATE-TOKEN: ubABrGEnkAApPj1-zKrf" "https://gitlab.informatik.uni-bremen.de/api/v4/projects/bsimon%2Fk-servers-predictions/jobs/build/artifacts"
```