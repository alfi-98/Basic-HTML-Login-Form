# Basic-HTML-Login-Form
This is a walkthrough of building a Login Form using HTML and CSS.  

## 1. IDE:
- For this project we are going to use ```VScode``` (Visual Studio) code editor

## 2. Project setup:
- Create a folder inside vscode and create a ```index.html``` file.
- To have a basic ```html``` structure type, ```! + Enter```
- Your file shoule look somthing like this:
<img width="1435" alt="Screenshot 2022-11-07 at 3 36 32 PM" src="https://user-images.githubusercontent.com/66726759/200276984-ce22cd15-c89a-4e21-a8f8-84d137cbf12c.png">


## 3. "Building the Login Page using HTML":

- ## Login Page Heading 
- At first we give a heading to our login page using ```<h1>``` tag. </br>
```<h1> Login page </h1>``` 
- Next, to create a section in the html page we use the ```<div>``` tag which has a ```class``` attribute  with value ```"login"```.</br>
- Inside the div we include a ```<form></form>``` tag. </br>
```
<div class="login">    
    <form>    
         
    </form>     
</div>  
```
- Then we use the ```<label>``` tag to label the input fields.
- ```<input>``` tag helps us to create input fields for the username and password. </br>
```
<h1>Login Page</h1><br>    
    <div class="login">    
    <form id="login" method="get" action="login.php">    
        <label><b>User Name     
        </b>    
        </label>    
        <input type="text" name="Uname" id="Uname" placeholder="Username">    
        <br><br>    
        <label><b>Password     
        </b>    
        </label>    
        <input type="Password" name="Pass" id="Pass" placeholder="Password">    
        <br><br>    
        <input type="button" name="log" id="log" value="Log In Here">          
          
    </form>     
    ```

