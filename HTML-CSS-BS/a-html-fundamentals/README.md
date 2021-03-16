# Building a Simple HTML Page
---
## Purpose

We designed this beginner's tutorial with the purpose of helping developers who are new to the HTML language and want to make some simple pages. The tutorial covers HTML fundamentals such as the basic HTML elements needed for a webpage and enough information to get you started. It also provides information on how to quickly and easily view your HTML pages in a browser. 

### Getting Started: Prerequisites

All you need to get started is Text Editor and Browser of choice.

- **Visual Studio Code**: For this tutorial, we will use Microsoft Visual Studio Code in order to edit our HTML code. You may choose to use another text editor if you feel comfortable doing so.

- **Google Chrome**: For this tutorial, we will use Google Chrome in order to view our HTML pages. You may choose another browser if you prefer.

## Step 1: Open VS Code

You can either create a new folder inside of VS Code or you can open VS Code at a particular folder location. Running the following command in a terminal will open VS Code at that file directory.

    code .

You can specify any directory with an absolute approach to the command as well:

    code C://ExampleUser/ExampleFolder1/

## Step 2: Create HTML File

To add a new file to your folder look to the Explorer Tab on the left hand side. This is typically already open for first time users. Hover over the name of your folder to find the Add File button.

Simply make sure that the file has a .html at the end, denoting its file extension. Any name should suffice.

    hello.html

## Step 3: Start Coding your HTML page

The first thing to note is that modern browsers are very fault tolerant. This means that, unlike other languages, you can skip out on some of the details or code in an HTML page and your browser will attempt to interpret the code for you.

Please refer to the html-demo folder for examples to test out.

That being said, let's outline the code for a basic HTML page with its essential parts known as Elements or tags:

    <!DOCTYPE html>
    <html>
    <head></head>
    <body>Hello World!</body>
    </html>

For details on specific tags and what they do, please use the Lecture Notes on HTML Fundamentals under the HTML CSS modules.

## Step 4: Opening your HTML page

For the focus of strictly teaching HTML we are going to showcase how to open your HTML page in the simplest way possible. 

### Copy File Path in VS Code

To open your HTML file via VS Code, we will need its file path. This is a directory location of the file on your computer. 

To copy the File Path, simply find your file in the Explorer, typically located on the left hand side, right click the file, and click Copy Path.

![Image of Copy Path](./images/CopyPath.PNG)

### Open File Path in Browser

Start by opening up Google Chrome or a similiar browser, or open a new tab if one is already open.

Paste in the File Path that was copied into the URL field at the top and hit ENTER. This will navigate you to your HTML page.

## Step 5: Add to the HTML File

Now that you can create and open an HTML file you are ready to enhance your work with additional HTML tags. For more information on how to use these tags please refer to the Lecture Notes in the HTML/CSS Modules folder. Please see SampleHTMLTags.html for a quick outlook of how a few tags can work.

In the next example we will build off of this one in order to make an HTML Form.