 ## Templating with Mustache
 ![image](https://miro.medium.com/max/700/1*LbqYj87xlazySm6wE0Q2lA.png) 
 
 Mustache-Express
If you intend you use mustache with Node and Express, you can use mustache-express. Mustache Express lets you use Mustache and Express together easily.
To install:
With Yarn:
$ yarn add mustache-express
or with NPM:
$ npm install mustache --save


![image](https://user-images.githubusercontent.com/77915248/112104568-0b023400-8bb4-11eb-980d-d0826c87e4d5.png)

___________________________________________________________________________________________________________________________________________________________
## Guide to Flexbox


![image](https://user-images.githubusercontent.com/77915248/112104961-7ea44100-8bb4-11eb-8e7e-1c6236df89c5.png)


![image](https://user-images.githubusercontent.com/77915248/112105022-94196b00-8bb4-11eb-8482-33fbe1856c38.png)


This defines the ability for a flex item to grow if necessary. It accepts a unitless value that serves as a proportion.
It dictates what amount of the available space inside the flex container the item should take up.

If all items have flex-grow set to 1, the remaining space in the container will be distributed equally to all children. 
If one of the children has a value of 2, the remaining space would take up twice as much space as the others (or it will try to, at least).

![image](https://user-images.githubusercontent.com/77915248/112105098-adbab280-8bb4-11eb-9479-b98c062411b6.png)

flex-flow
This is a shorthand for the flex-direction and flex-wrap properties, which together define the flex container’s main and cross axes.
The default value is row nowrap.

.container {
  flex-flow: column wrap;
}

