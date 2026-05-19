1. Answer: Within a GitHub action that runs whenever code is pushed

This is the best place to put the automated tests because this way it makes sure that the tests funa nd check the code consistently every time the code changes. That way, if there ever is an error, it finds the problem before it gets pushed into the main branch, to make sure faulty code is not being pushed onto the main branch.

2. Answer: No

I would not use an End-to-End test to test a function because End-to-End testing tests from a user perspective and just looks at if it works, but it does not look at the code directly, so it would be bad for testing isolated code functions

3. Answer: The difference between navigation and snapshot mode is that navigation analyzes the page in the beginning when it initially loads and measures the overall performance of its loading, but it cannot analyze anything after that when the user interacts with the page. Snapshot mode, on the other hand, analyzes the page in the current state, which enables it to test accessibility and if there are any issues, but it is not good at analyzing performance.

4. Answer: Three things that could be improved:

    * Add a title attribute to frame or iframe elements
    * Add a [lang] attribute to the html element.
    * Resolve the background warnings and errors that were logged in the Chrome DevTools "Issues" panel.

Sean Zemlyak

https://szemlyak1.github.io/Lab7-Starter/
