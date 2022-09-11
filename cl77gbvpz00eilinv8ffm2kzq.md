## TAILWIND CSS | Everything you need to know about CSS Framework!

**what is Tailwind CSS?**🤔
===========================

 Tailwind CSS is a utility-first CSS system for quickly fabricating custom UIs. It is profoundly centered around a portable first methodology like Bootstrap. An adaptable and low-level CSS system gives all the structure blocks to make plans with no styles.

**why Tailwind CSS?**🤔
=======================

 *   Quicker UI building process
 *   It is a utility-first CSS system which implies we can utilize utility classes to construct handcrafts without composing CSS as in the customary methodology.
 *   Tailwind CSS is a low-level system, Meaning dissimilar to other CSS structures like Bootstrap and Materialize, Tailwind doesn't offer completely styled parts like buttons, dropdowns, and navbars. All things considered, it offers utility classes so you can make your reusable parts.

Thus, it gives much greater adaptability and commands over what your application resembles than other CSS systems. This can empower you to make a more novel site.

🎯 **Advantages**
=================

 *   Not any more senseless names for CSS classes and Id.
 *   Least lines of Code in CSS record.
 *   We can redo the plans to make the parts.
 *   Makes the site responsive.
 *   Rolls out the improvements in the ideal way.

* * *

🎯 **Getting Started**
======================

 Tailwind CSS works by checking all of your HTML records, JavaScript parts, and some other layouts for class names, creating the relating styles, and afterward thinking of them to a static CSS document. It's quick, adaptable, and solid — with zero runtime.

🎯 **add Tailwind CSS utilizing Play CDN**
----------------------------------

1. Add the play CDN script tag to the 'top' of your HTML record.

     
    
     
    
     
    
         <script src="https://cdn.Tailwind CSScss.com"</script
    

2. Have a go at Customizing your config Edit the 'Tailwind CSS. config' object to redo your setup with your plan tokens.

     
    
     
    
     
    
         <script
          Tailwind CSS.config = {
            topic: {
              expand: {
                colors: {
                  Clifford: '#da373d',
                }
              }
            }
          }
         </script
    

3. All have a go at adding some custom CSS Use 'type=" text/Tailwind CSScss"' to add custom CSS that upholds Tailwind's CSS highlights.

     
    
     
    
     
    
         <style type="text/Tailwind CSScss"
           @layer utilities {
             .content-auto {
               content-permeability: auto;
             }
           }
         </style
         <body
         <div class="lg:content-auto"
           <!-- ... --
         </div
         </body
    

4. Have a go at utilizing the first-party module Enable first-party modules, similar to structures and typography, utilizing the 'modules' inquiry boundary.

     
    
     
    
     
    
         <!doctype html
         <html
         <head
         <meta charset="UTF-8"
         <meta name="viewport" content="width=device-width, starting scale=1.0"
         <script src="https://cdn.Tailwind CSScss.com?plugins=forms,typography,aspect-ratio,line-clamp"</script
         </head
         <body
         <div class="prose"
          <!-- ... --
         </div
         </body
         </html
    

* * *

🎯 Utility-First Fundamentals
=============================

 

 

 

     <div class="p-6 max-w-sm mx-auto bg-white adjusted xl shadow-lg flex things focus space-x-4"
       <div class="shrink-0"
         <img class="h-12 w-12" src="/img/logo.svg" alt="ChitChat Logo"
       </div
       <div
         <div class="text-xl text style medium text-black"ChitChat</div
         <p class="text-record 500"You have a new message!</p
       </div
     </div


 In this model, we have utilized

 *   Tailwind's **flexbox** and **padding** utilities ('flex', 'recoil 0', and 'p-6') to control the general card format
 *   The **max-width** and **margin** utilities ('max-w-sm' and 'MX-auto') to evenly oblige the card width and focus it
 *   The **background color**, **border-radius**, and **box-shadow** utilities ('bg-white, 'adjusted xl', and 'shadow-lg') to style the card's appearance
 *   The **width** and **height** utilities ('w-12' and 'h-12') to measure the logo picture
 *   The **space-between** utilities ('space-x-4') to deal with the dividing between the logo and the text
 *   The **font size**, **text color**, and **font-weight** utilities ('text-xl', 'text-dark', 'text style medium', and so on) to style the card text

 with the assistance of this methodology, we can execute a custom part plan without composing a solitary line of custom CSS.

* * *

🎯 Dealing with Hover, Focus, and different States
==========================================

 Tailwind incorporates modifiers for basically all that you'll at any point require, including:

 *   **Pseudo-classes**, as ':drift', ':concentrate', ':first-aid, and ':required'
 *   **Pseudo-elements**, as '::in the past, '::later', '::placeholder', and '::choice'
 *   **Media queries**, as 'responsive breakpoints', 'dim mode', and 'favors decreased movement'
 *   **Trait selectors**, as '[dir="RTL"]' and '[open]'

 **drift, center, active**
 ------------------------

 

 

 

     <button class="bg-violet-500 hover:bg-violet-600 active:bg-violet-700 focus:outline-none focus:ring focus:ring-violet-300 ..."
       Save changes
     </button


 **previously and after**
 --------------------

 ### **before**

 

 

 

     <blockquote class="text-2xl text style semibold italic text-focus text-record 900"
       At the point when you look
       <range class="before:block before:absolute previously:- inset-1 preceding:- slant y-3 before:bg-pink-500 relative inline-block"
         <range class="relative text-white"annoyed</span
       </span
       constantly, individuals feel that you're occupied.
     </blockquote


 ### **after**

 

 

 

     <mark class="block"
       <range class="after:content-['*'] after:ml-0.5 after:text-red-500 block text-sm text style medium text-record 700"
         Email
       </span
       <input type="email" name="email" class="mt-1 px-3 py-2 bg-white line shadow-sm line record 300 placeholder-record 400 focus:outline-none focus:border-sky-500 focus:ring-sky-500 block w-full adjusted MD sm:text-sm focus:ring-1" placeholder="you@example.com"/
     </label


* * *

🎯 Responsive Design
====================

 sm

  least width 640px CSS [@media](https://hashnode.com/@media) (min-width: 640px) { ... }

 MD

  least width 768px CSS [@media](https://hashnode.com/@media) (min-width: 768px) { ... }

 LG

  least width 1024px CSS [@media](https://hashnode.com/@media) (min-width: 1024px) { ... }

 xl

  least width 1280px CSS [@media](https://hashnode.com/@media) (min-width: 1280px) { ... }

 2xl

  least width 1536px CSS [@media](https://hashnode.com/@media) (min-width: 1536px) { ... }

🎯 **Portable First**
-------------------

 Of course, Tailwind utilizes a portable first breakpoint framework, like what you may be utilized to in different systems like Bootstrap.

 

 

 

     <!-- This will focus the text on portable, and left adjust it on screens 640px and more extensive - - 
     <div class="text-focus sm:text-left"</div


🎯 **Focusing on a solitary breakpoint**
------------------------------------

 

 

 

     <div class="bg-green-500 md:bg-red-500 lg:bg-green-500"
       <!-- ... --
     </div


🎯 **Redoing breakpoints**
------------------------------

 You can redo your breakpoints in your **Tailwind CSS.config.js** record:

 

 

 

      module.exports = {
        topic: {
          screens: {
            'tablet': '640px',
            // = @media (min-width: 640px) { ... }
            'PC': '1024px',
            // = @media (min-width: 1024px) { ... }
            'work area': '1280px',
            // = @media (min-width: 1280px) { ... }
          },
         }
       }


* * *

### 🎯 **Resources**

 *   [Tailwind Doc](https://Tailwind CSScss.com/docs/establishment)
 *   [GFG](https://blog.hubspot.com/site/what-is-Tailwind CSS-css)
 *   [blog](https://www.geeksforgeeks.org/prologue to-Tailwind CSS-css/#:~:text=Tailwind%20CSS%20is%20basically%20a,have%20to%20fight%20to%20override.)

