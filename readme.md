# Testing environment with Jest and Babel

This repo is a JavaScript testing environment, it uses Babel and lite-server for refreshing and displaying the jest html reporter. They can both be fully configured, see their docs for further details.

1. Install with `npm i`
2. Write tests inside `__tests__`
3. To run tests in the cli, use `npm run test`
4. For the Html report that refreshes on changes, run `npm start`. This uses nodemon to avoid cross platform issues with Jest's watch command.
