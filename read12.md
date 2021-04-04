# EJS PARTIALS

Partials come in handy when you want to reuse the same HTML across multiple views. 
Think of partials as functions, they make large websites easier to maintain as you 
don’t have to go and change a piece of text in every page it appears in. Instead,
you define that reusable bundle of code in a file andinclude it wherever you need it.


To begin, ensure you have EJS and express installed via npm.
so , The Correct way to include partials in the template according to this you should use:

><%- include('partials/youFileName.ejs') %>

EJS partials, which are used to help us to avoid repetition of the same code on several web pages.



Including a partial in EJS is quite straightforward. You use <%- include( PARTIAL_FILE ) %> where the partial file is relative to the template you use it in.
Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include()
statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’, etc…
