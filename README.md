## Test-front

Website preview https://test-front-boticario.netlify.app/

![GH-Actions](https://github.com/henriqueweiand/test-front/workflows/GH-Actions/badge.svg)

[![Netlify Status](https://api.netlify.com/api/v1/badges/7009114e-82a5-4d98-b818-6916d6c043c0/deploy-status)](https://app.netlify.com/sites/test-front-boticario/deploys)

## Frontend Test

Fork this repository and finish testing, submit a pull request to the repository and our team will be notified.

The test consists of a simple checkout containing 3 steps (cart, payment and success) [See the Layout](https://projects.invisionapp.com/prototype/font-test-cji0j0khf005c1t0132358e8k)

**Do it whenever you want/can (early morning, weekend, etc.)**

### Requirements

- Pixel perfect ([nesse link](https://projects.invisionapp.com/prototype/font-test-cji0j0khf005c1t0132358e8k), you can inspect for spacing, font, size, etc)
- The application needs to be responsive, using the concept of mobile-first. Use your imagination to deliver a great desktop experience.
- Render each step to a unique URL (route lib).

### Step 1 - Cart:

- Consume the [this endpoint](http://www.mocky.io/v2/5b15c4923100004a006f3c07) and list the cart items as well as the cart summary;
- Persist the JSON content to be used in the next steps;

### Step 2 - Payment:

- Display a form with credit card fields with validation in each field;
- Enable the Finish Order button only if the form is valid;

### Step 3 - Success:

- All content must be displayed from the persisted data;

### What we will evaluate:

- Organization of the code;
- Messages (in English) and changes in commits;
- Composition/reuse of components;
- Unitary tests;
- The reason for choosing each tech in the stack;
- How to run your application ;)

### Differentials:

- Split bundle per route (each step will have a separate bundle to optimize performance);
- CSS in JS;
- React;

### And:

When the test is finished, submit a pull request to the repository and our team will be notified. If you have any observations, write them in the pull request.
