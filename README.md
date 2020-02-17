# BostickWebAutomation
Is an easy to use C# (.NET Framework) Web Automation soluiton with built-in reports, that works out of the box.

Now, there is no longer a need to setup and configure a bunch of frameworks and/or tools to get started.  All you need to do is, simply,  download or clone the solution, run the solution to see how the example (Demo.cs) works.  Then, all you need to do to get started is adjust the "Demo.cs" file to meet your testing needs.  

BostickWebAutomation is flexible, meaning, you can create a new C# class under the "Pages" folder, inspect every web page (under test), then add each web element (e.g. inputs, links, ect..) as a variable to your class.  Furthermore, you can add a individual Test Cases under the "TestCases" folder that will call on the variables you created in the C# classes within the "Pages" folder.

## Examples
```
# This will open a new Chrome Browser
Browser.Open("type the url of the web site under test") 

```
