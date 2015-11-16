#github-api-profile

## Objectives

### Learning Objectives

After completing this assignment, you should:

* Be able to fetch data and render it with React.


### Requirements

* No JS errors in the browser
* Use React, React.DOM to build the assignment.
* All functions and code should work according to the following description:

Build a github profile app that prints out some info from the Github API and your repos. __For the design, you should recreate the Github Repos Tab to the best of your ability__.

> Github tab page: https://github.com/nicerhugs?tab=repositories

The information from the Github API that you will display includes information from your github user account and repositories.

- Write `$.ajax()` requests to:
    - `https://api.github.com/users/<username>`
    - `https://api.github.com/users/<username>/repos`

- After loading data from the Github API, write at least the following information to the DOM:
    - name
    - blog
    - location
    - email
    - avatar_url
    - html_url
    - and list all of your repositories


## Additional Resources
- [React Docs](https://facebook.github.io/react/docs/getting-started.html)
- [Getting Started](https://blog.risingstack.com/the-react-way-getting-started-tutorial/)
