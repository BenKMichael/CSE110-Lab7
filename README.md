## Name

Benjamin Michael

## Check Your Understanding

1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Within a Github action that runs whenever code is pushed**

Having automated tests being part of a Github action would be best practice. This allows tests to be run whenever a push is made which allows every minute change to the codebased to be checked and verified. It also broadcasts when tests fail so all collaborators are made aware of whats failing and when the failure occured.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No 

3) What is the difference between navigation and snapshot mode?

Navigation mode evaluates website performance on initial load whereas snapshot mode evaluates website performance in its current state. Use case is general for the former and more targeted for the latter.

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. A [lang] attribute can be given to <html> element to improve localization.
2. Document should be given meta description to summarize page content in search results.
3. JavaScipt files can be minimized to improve performance.