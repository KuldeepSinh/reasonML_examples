# hello-reason-react

## Run Project

```sh
npm install
npm start
# in another tab
npm run webpack
```
After you see the webpack compilation succeed (the `npm run webpack` step), open up `src/index.html` (**no server needed!**). Then modify whichever `.re` file in `src` and refresh the page to see the changes.

**For more elaborate ReasonReact examples**, please see https://github.com/reasonml-community/reason-react-example

User Story
When I launch the app in a browser
Then I should see the web page with message = "Hello, Reason React!"

User Story
Given I have opened the web app in a browser
And the page shows "Hello, Reason React!" message
When I click on the message
Then the console log shows a log with text = "Clicked, HelloMsg!" 
