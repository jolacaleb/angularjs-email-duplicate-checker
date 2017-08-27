# angularjs-email-duplicate-checker

- make GET RESTful api which returns email address already exists if api returns boolean data
   - example: 
 ```html
 <input api="/api/v1/users" query="email" ng-model="vm.form.email"/>
```
 
     
 will call api 
     
    
 ```javascript
 '/api/v1/users?email={{ vm.form.email }}'
 ```

- the api should return a boolean data
  - true: the email address already exists
  - false: the email address does not exist

- should make RESTful API yourself which returns right value.
