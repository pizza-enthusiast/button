Using this to generate errors in Sentry:

First, clone the following repository, navigate to the main ./button directory and run "npm update": https://github.com/pizza-enthusiast/button

Second, I would create a sample Angular project from your Sentry dashboard here: https://sentry.io/organizations/YOUR-USERNAME-HERE/projects/new/

Third, copy the configuration info from the following page into ./button/src/app/app.modules.ts : https://sentry.io/YOUR-USERNAME-HERE/angular-hi/getting-started/javascript-angular/

Fourth, once your info is in there, start up Angular locally (ng serve --open) and click the "CLICK HERE!" button. This should throw an "myFunction is not defined" error to your Sentry dashboard.
