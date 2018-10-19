# ant-design-bug-repro-repo
A skeleton repo with a reproduced bug 

Install and Initialization#
Ensure your system has installed latest version of yarn or npm.

Create a new project named antd-demo-ts using yarn.

$ yarn create react-app antd-demo-ts --scripts-version=react-scripts-ts
If you are using npm (we will use yarn in the following instructions, it's ok to replace yarn with npm)

$ npm install -g create-react-app
$ create-react-app antd-demo-ts --scripts-version=react-scripts-ts
Then we go inside antd-demo-ts and start it.

$ cd antd-demo-ts
$ yarn start
Open browser at http://localhost:3000/, it renders a header saying "Welcome to React" on the page.

Import antd#
$ yarn add antd

To see the bug
