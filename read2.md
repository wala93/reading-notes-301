# 6 Reasons for Pair Programming

1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. 

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers
are more focused than if they were working alone.

3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose 
developers to techniques they otherwisewould not have thought of. If one developer
has a unique approach to a specific problem, pair programming exposes the
other developer to a new solution.

4. Social skills
Pair programming is great for improving social skills. When working with someone who has 
a different coding style, communication is key. This can become more difficult when
two programmers have different personalities. Pair programming not only improves
programming skills, but can also help programmers develop their interpersonal skills. 

5. Job interview readiness
A common step in many interview processes involves pair programming between a current
employee and an applicant, either in person or through a shared screen.

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree 
programs on how they operate to actually deliver a product.


________________________________________________________________________________________________________________________________________________
# JavaScript and jQuery

jQuery offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major 
browsers and without any fallback code needed. 

![image](https://user-images.githubusercontent.com/77915248/111945309-2997fa80-8ae2-11eb-92db-eb1cec53e519.png)


## WHY USE JQUERY? 
jQuery doesn't do anything you cannot achieve with pure JavaScript. 
It is just a JavaScript file but estimates show it has been used on over a 
quarter of the sites on the web, because it makes coding simpler.


![image](https://user-images.githubusercontent.com/77915248/111945571-a0cd8e80-8ae2-11eb-900c-eae6d49e1e41.png)


## GETTING ELEMENT CONTENT 
The • htm 1 () and • text () methods both retrieve and update the content 
of elements. This page will focus on how to retrieve element content. To 
learn how to update element content, see p316 .


## GETTING AND SETTING ATTRIBUTE VALUES 

you can create attributes, or access and update their contents, using the following four methods. 
You can work with any attribute on any element using the attr() 
and r emoveAttr() methods. 

![image](https://user-images.githubusercontent.com/77915248/111946198-b099a280-8ae3-11eb-9f8b-69893bb7566c.png)


## EFFECTS 
When you start using jQuery, the effects methods can enhance your web 
page with transitions and movement. 





![](![image](https://user-images.githubusercontent.com/77915248/111944491-6d8a0000-8ae0-11eb-9160-d57765f8b3e7.png)

## BASIC EFFECTS 
In this example, it appears as 
if list items are faded into view 
when the page loads. Each item 
is faded out when it is clicked on. 
JAVASCRIPT 

In fact, the items are loaded 
normally along with the rest of 
the page, but then immediately 
hidden using JavaScript. 


>$(function() { 
>$('h2').hide().slideDown(); 

>var $li = $('li'); 

>$li.hide().each{function(index) {
 
>2 $(this).delay(700 * index) .fadeln(?OO); 

>} ) ; 

>3 
>$li.on('click', function() 

>$(this) .fade0ut(700); 

>} ) ; 
>} ) ; 



## ANIMATING CSS 
PROPERTIES 
The .animate() method allows you to create 
some of your own effects and animations by 
changing CSS properties. 


## JAVASCRIPT 
$(function() { 
USING ANIMATION 
When the user clicks on a list 
item, it fades out and the text 
content slides to the right. 
(This takes 500ms.) Once 
that is complete, a callback 
function removes the element. 
You can increase or decrease 
numeric values by a specific 
amount. Here, +=80 is used to 
increase the padding property 
by 80 pixels. (To decrease it by 
80 pixels, you would use -=80.) 
c07/ js/animate.js 
d $(' l i').on( 'click', function() { 
~ $(this).animate({ 
~r opacity : 0.0, 
~ paddingleft: '+=80' 
@ } , 500, function() { 
~ $(this).remove(); 
} ) ; 
} ) ; 
} ) ; 


____________________________________________________________________________________________________________________________________




![image](https://user-images.githubusercontent.com/77915248/111945024-965ec500-8ae1-11eb-9678-05df6e5893fe.png)


## DOING THINGS WITH YOUR SELECTION 


Once you have selected the elements you want to work with (and they 
are in a j Que ry object), the jQuery methods listed on these two pages 0 
perform tasks on those elements. 


