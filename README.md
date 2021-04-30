# Bem__Stuff

# Introduction to BEM Methodology 

Now, let’s talk about BEM!

## What is BEM?

BEM stands for Block, Element, Modifier.
⁣
 BEM is a popular naming convention for classes in HTML and CSS. Its goal is to help developers better understand the relationship between the HTML and CSS in a given project. ⁣


## Why use BEM ?

   👉 When you are building smaller websites, how you organize your styles is usually not a big problem. You create your usual files, write all the needed CSS, and that’s all. 		However, when it comes to larger, more complex projects, how you organize your code becomes crucial. How the code is structured is even more important if you are working in    a team consisting of multiple front-end and back-end developers.
 
 👉 CSS is a language that’s easy to learn but very hard to maintain. As the project grows larger, without proper structure, maintaining CSS is unbearable, hence we use the B EM methodology to make CSS maintainable. </p>
      
  👉 Another smart part of BEM is that everything is a class and nothing is nested. That makes CSS specificity very flat and low, which is a good idea. It means you won’t end up fighting with yourself over specificity.

## PROS of using BEM

 ``` 
👉  BEM provides a modular structure to your CSS project. Because of its unique naming scheme,
     we won’t run into conflicts with other CSS names. BEM also provides a relationship between CSS and HTML.
     Ambiguous names are hard to maintain in the future⁣.

👉   BEM Methodology will massively improve code maintainability and speed up the development process

👉   Note that the best practice is to use BEM only with classes, and not IDs because classes allow you to repeat names.
      if necessary and create more consistent coding structure. 
 
 ``` 

## using BEM
 ``` 
original naming conventions, modifier would be defined like this:

``` .block__element_modifier  ```

Harry Roberts style example:

``` .block-name__element-name--modifier-name ```

CamelCase style example:

``` .BlockName__ElementName_ModifierName ```

 ``` 

Overall, BEM is my favourite CSS naming scheme, and I strongly suggest you try using it too!

It will save you SOOO much debugging time in the future.⁣
⁣
# More Reference

https://scalablecss.com/

https://css-tricks.com/bem-101/

https://scalablecss.com/bem-blocks-within-blocks/
