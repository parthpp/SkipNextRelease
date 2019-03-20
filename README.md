This is a handy project to experiment with a proposed new feature in [Docusaurus](https://github.com/facebook/Docusaurus).  Please refer to PR# for details of the feature.

In order to test this feature follow these steps
1. Clone this repository
2. Clone [my clone of Docusaurus](https://github.com/parthpp/Docusaurus) and checkout `skipNextDocs` branch
3. Navigate to `This Repository/website/package.json` replace docusaurus dev dependency
4. Do a `yarn install` 
5. Run the command `yarn build --skip-next-release`