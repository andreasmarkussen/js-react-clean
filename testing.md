
# Notes on testing

Running a test is as simple as 

   yarn test

This runs the Jest Test tool, 

However it takes between 5 and 15 seconds to run the test, so this seems slow, but it is the overhead of starting up the test framework, that is slow. 
If you run it with --verbose then it show that the individual test are not slow -- unit test below 5 ms and ui component test below 50 ms. 

   yarn test -- --verbose

Alternatively I was looking into using Cucumber to see if this is faster.. 

And these two articles could be relevant

https://medium.com/@anephenix/end-to-end-testing-single-page-apps-and-node-js-apis-with-cucumber-js-and-puppeteer-ad5a519ace0

https://medium.com/@Charles_Stover/behavior-driven-react-development-with-cucumber-faf596d9d71b

