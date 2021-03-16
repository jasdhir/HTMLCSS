# Building Simple HTML Forms
---
## Purpose

We designed this beginner's tutorial with the purpose of helping developers who are new to the HTML language and want to make some simple pages. The tutorial covers HTML Forms including the basic HTML elements needed for an HTML Form and enough infromation to get you started. 

### Getting Started: Prerequisites

All you need to get started is a Text Editor and Browser of choice. Additionally, basic knowledge of creating HTML pages would help. See HTML Foundations Examples for more insight.

- **Visual Studio Code**: For this tutorial, we will use Microsoft Visual Studio Code in order to edit our HTML code. You may choose to use another text editor if you feel comfortable doing so.

- **Google Chrome**: For this tutorial, we will use Google Chrome in order to view our HTML pages. You may choose another browser if you prefer.

## Step 1: Set Up an HTML file

Follow previous instruction for creating an HTML file. To do so in Visual Studio Code, click on: New -> New File. Make sure to end the file name with .html to add the html file extension. Example:

    hello.html

Once the file is created, add any basic HTML elements you wish in preparation for creating a form.

## Step 2: Add in HTML Forms

For more details on specific HTML Form Elements, see the Lecture Notes in the HTML CSS Modules on HTML Forms. The goal here is to instruct on how to add a Form. Make sure to refer to the example HTML file provided in b-html-forms folders.

Below is some code to get you started with a basic HTML Form.

    <form>
        <label for="email-input">Email Id:</label><br> 
        <input type="text" name="email-input" />
    </form>

The Input Fields are used to receive information from the user of the HTML page.

Beyond this, it's up to the developer to decide what else they want an HTML Form to do. Below is an extended example of what can be in a form:

     <form action="/SomeServlet" method="post" id="users"> 
        <label for="username">Username:</label> 
        <input type="text" name="username" id="Username" />

        <br> 
        <input type="checkbox" name="subject" id="math" /> 
        <label for="math">Math</label> 
        <input type="checkbox" name="subject" id="science" /> 
        <label for="sceince">Science</label> 
        <input type="checkbox" name="subject" id="english" /> 
        <label for="english">English</label> 

        <br>
        <label for="country">Country:</label> 
        <select name="country" id="country"> 
            <option value="United States">United States</option> 
            <option value="Canada">Canada</option> 
            <option value="Mexico">Mexico</option> 
        </select>

        <br>
        <label for="fileselect">Upload:</label> 
        <input type="file" />
        <input type="submit" value="Submit" /> 
        <input type="reset" value="Reset" /> 
    </form> 


**Note**: Modify the labels and data as needed for your examples.

## Step 3: Test Form in a Browser

Follow the steps outlined in the HTML Fundamentals Example for opening your HTML within a browser. You will need to copy the File Path of the HTML page you wish to open and paste that into your browser of choice.