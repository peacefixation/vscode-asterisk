# Deployment Instructions

## Update Files

- increment the version in package.json
- update the changelog
- commit and push both files
- tag the release: `git tag -a vX.X.X -m "Release vX.X.X"`
- push the tag: `git push origin vX.X.X`

## Publish

https://code.visualstudio.com/api/working-with-extensions/publishing-extension

Install vsce: `npm install -g vsce`  
Visit https://dev.azure.com/peacefixation  
Generate a Personal Access Token with scope "Marketplace: Manage"  
Run `vsce login peacefixation` and supply the token  
RUN `vsce publish`  
