# Async API spectral and codegen demo

- Get started by installing spectral latest beta version
```
npm install -g @stoplight/spectral@5.4.0-beta1
```

- Take a look at `.spectral.yml` file for an example of extending rulesets. You can use this file to add custom rules to lint against. 

- Lint your api file using:
```
spectral lint streetlights.yml
```

- Next, install async api generator using
```
npm install -g @asyncapi/generator
```

- Find a template at https://github.com/asyncapi/ . We'll go with the node template

- Generate code using:
```
ag streetlights.yaml @asyncapi/nodejs-template -o output -p server=production
```

Also please find the slide deck in the repo. 

*Nauman Ali*

https://www.linkedin.com/in/nauman-ali/