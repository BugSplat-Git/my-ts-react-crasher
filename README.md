[![BugSplat](https://s3.amazonaws.com/bugsplat-public/npm/header.png)](https://www.bugsplat.com)
## my-ts-react-crasher
This repo is an example of how to use BugSplat's [npm package](https://www.npmjs.com/package/bugsplat) in a React application.
1. Clone this repository and run `npm install`
2. Run `npm run start:build` to build and start the app outside of Reacts debugger, this is important because otherwise React will intercept the crashes
3. Navigate to [127.0.0.1:8080](http://127.0.0.1:8080) and click one of the buttons to trigger a crash
4. Navigate to BugSplat's [Crash](https://app.bugsplat.com/v2/crashes?database=Fred&c0=appName&f0=CONTAINS&v0=my-ts-react-crasher) page in your web browser
5. When prompted to log in, use the username "Fred@bugsplat.com" and password "Flintstone"
6. Click the ID of your crash to see crash details

For additional help, check out the [documentation](http://www.bugsplat.com/docs/) on our website or email support(at)bugsplat.com if you have any questions.

Good luck!
© BugSplat Software
[Web](https://www.bugsplat.com) | [Twitter](https://twitter.com/BugSplatCo) | [Facebook](https://www.facebook.com/bugsplatsoftware/)