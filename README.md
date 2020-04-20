The project is implemented by Vuejs and CSS without Bootstrap

- Business logic:
   - Given there are 5 types of questions: rating, age, email, password and comment.
   - Once any question is answered, on the right appears a "result widget" with all the given questions and answers.
- On the mobile design:
  - "result widget" is not shown in the mobile view.
  - The age question is split into 3 lines. 
  
   <img src="https://github.com/nassimtaghipour/form-rating/blob/master/public/3.png" width="300" height="400">
 - Validation rules for the form:
   - The field `"required"` from the example json data must be taken into account.
   - Password must contain at least 1 lowercase letter and a number.
   - Email question must pass a simple validation.
 - On Submit, show either "success" or "not valid" somewhere on the page (on your choice).
 - Each question can have a sub-question which appears based on a value given to its parent question.
   for example: sub1 appears if parent question got value 1-2
   sub2 appears when parent value 4-5 and nothing appears on value 3

   
   <img src="https://github.com/nassimtaghipour/form-rating/blob/master/public/2.png" width="500" height="400">
 

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

