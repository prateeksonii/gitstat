# GitStat

You're going to build a react web app that takes a username as input and display the following properties for the given user:

- HTML URL
- Bio
- Avatar image
- No. of public repos
- No. of public gists
- No. of followers

It should look good, be responsive and the code should follow the standards.

## TODO

- [ ] Fork this repo to your account and clone it.
- [ ] Initialize a react application in the same folder. Call it `app`.
- [ ] Create a landing page, with a good-looking hero section describing the application.
- [ ] Add a text input below the hero section to enter the github username.
- [ ] Add a form surrounding the input, which when submitted, should navigate you the a new page, call it /[username].
- [ ] Once this page starts loading, fetch the details for the given username. Use `fetch` to make the `GET` request.

  - Here's the endpoint to retrieve the information: [https://api.github.com/users/[username]](https://api.github.com/users/[username])
  - Example: [https://api.github.com/users/facebook](https://api.github.com/users/facebook)
    [] Save only the required fields in the component state.
    [] Display the state values as you see fit.

> Expected Time: 2-3 hours

### Recommendations:

- Install/Use `ESLint` extension to make sure you're following coding standards.
- Use `Vite` to create a new react application
