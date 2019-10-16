# libEjsBootstrap
Simple library for EJS for form field based on bootstrap

## How to use
- copy folder in your reference template folder
- import the template passing variable for compose form

````
<%- include('lib_ejs/inputField',{classX:'class col ' , 
                                  type:'type of inputbox' , 
                                  name:'name attribute' , 
                                  value:'value attribute' , 
                                  id:'id attribute', 
                                  required:'if not required delete it', 
                                  readonly:'if not required delete it'  }) %>
````
