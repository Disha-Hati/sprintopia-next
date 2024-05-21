

## Setting Up
The easiest way to get started with Next.js is by using create-next-app

```bash
npx create-next-app@14.0.4
```
To install yarn. Yarn is a package manager similar to npm
```bash
npm install -g yarn 
```
To check your yarn version
```bash
yarn --version
```
To avoid conflict with storybook and jest
```bash
yarn set version stable
```
Delete package-lock.json file, and run the following command to create yarn-lock file
```bash
yarn 
```
! Add .yarn in gitignore file to avoid pushing the unneccessary files

To run the file 
```bash
yarn dev
```

## Setting up Testing

To install testing libraries
```bash
yarn add @testing-library/jest-dom @testing-library/react @testing-library/user-event jest jest-environment-jsdom ts-jest
```
Add the following to scripts in package.json
```
"test":"jest --coverage",
"test:watch":"jest --watchAll"
```

Add Jest config file in root directory as jest.config.js

Add Jest setup file in root directory as jest.setup.js

## Setting up CI/CD Pipelines

1. Go to the github repository
2. Go to Actions tab
3. Choose Workflow. Under Continuous Integration, choose Node JS
4. Change the yml file name and commit changes
5. Pull the changes to local
6. Make the neccessary changes







