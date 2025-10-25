# Deployment Instructions

## Update Files

- increment the version in package.json
- update the changelog
- commit and push both files
- tag the release: `git tag -a vX.X.X -m "Release vX.X.X"`
- push the tag: `git push origin vX.X.X`

## Publish

Read the instructions:

- https://code.visualstudio.com/api/working-with-extensions/publishing-extension

Use `vsce` to publish the extension:

- Install vsce: `npm install -g @vscode/vsce`  
- Visit https://peacefixation.visualstudio.com  
- Generate a Personal Access Token with scope "Marketplace: Manage"  
- Run `vsce login peacefixation` and supply the token  
- Run `vsce publish`
