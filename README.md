Badass-o-matic student management-o-tron 9000
===

This is a thing that hopefully demonstrates how awesome
[ngResource](https://docs.angularjs.org/api/ngResource) is.

General steps to make this:

1. `yo angular-fullstack`: Run the generator. Go cure cancer while `npm` runs.

2. `yo angular-fullstack:route student`: Create the student list route (I gave
it `/students` as a URL). Add it to the navbar with `student` as the state
(`client/components/navbar/navbar.controller.js`).
