# EJS
<%= EJS %>
Embedded JavaScript templating.

It's easy to install EJS with NPM.

in terminal : $ npm install ejs
in server.js file : app.set('view engine', 'ejs');


EJS is fast way to template our application 
for example 

<% if (user) { %>
  <h2><%= user.name %></h2>
<% } %>
  
  
**SO** WE can say:
EJS is a template system. You define HTML pages in the EJS syntax and you specify where various
data will go in the page. Then, your app combines data with the template and "renders" a complete HTML 
page where EJS takes your data and inserts it into the web page according to how you've defined the template. 

EJS is compatible with Express for back-end use as it hooks into the View engine architecture
that Express provides and lets you render web pages to the client with res.render(). 


 this is example of using EJS :
 
 ![image](https://user-images.githubusercontent.com/77915248/113499961-fe220080-9522-11eb-9faf-d616702c22bf.png)
 
 
