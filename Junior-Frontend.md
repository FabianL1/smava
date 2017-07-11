# F1 - smava recruitment tasks for front-end developers

Hello! We are very happy to see that you have reached this challenge! The task requires some creativity, we are giving you some description, which is very close to the stuff, that we are actually working in smava.

Solutions need to be provided as a bunch of files. For this task you may want to use some build tools, so we are expecting source code from you but not the minified output because the code quality is also important for us.

We wish you best of luck and hope you will have a nice time while solving this task!


## Make a registration form

We would kindly ask you to show us your ability to create a form. You are allowed to choose any library or framework that will help you to get the job done, although we would prefer to see you working with Marionette or React.
Please don't spend more than 3 hours on this task. Please make sure that at the end you commented on what you have not managed to finish and please outline how you would solve the remaining work including an estimate of how much time it would have approximately taken you.


### Technical description

1. When a user opens a page he or she sees the following: ![first](https://cloud.githubusercontent.com/assets/11552532/25622469/c7842068-2f54-11e7-9c41-da9296c62669.png)

2. The specific input data shall be validated once the user finishes his field input and once again for all data just before the submission of the form to the backend (validation rules - please see bellow). In case of validation errors a
message shall be displayed next to the invalid field. ![third](https://cloud.githubusercontent.com/assets/11552532/25622572/191de2e2-2f55-11e7-9a27-b7254efd824e.png)

3. If the user has tried to submit invalid data first and fixed the validation errors afterwards, the whole data set should be validated again on submission.

### Validation rules

* All fields are mandatory

1. **firstName** - should contain only small and capital letters, no numbers, special characters, etc.
1. **lastName** - same as the **firstName**
1. **email** - must be a valid email address
