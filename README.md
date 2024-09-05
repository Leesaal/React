# React

React is a Javascript library, primarily focussed on UI.

### What is a library?

A library is a collection of pre-built, reuseable functions/code that are ready to be used within a project to optimise efficiency, performance and tasks.

And a javascript library is just a library written in javascript.

It is like wanting to make pancakes for breakfast and already having the pancake batter made for you so you only need to do the cooking. This saves you time from checking you have the ingredients, measuring the ingredients and mixing them together! That is how a library works and optimises tasks.

### What is UI?

UI is an acronym for User Interface. This is the look and feel of an application. So this includes the layout and presentation of a web page. For example: Where is the header? What font and size is the brand catchline? What image do we use for avatars?

### Why is React sometimes called a framework?

React is a library but you can get React-based frameworks (like Next.js).

React gives you components and code to structure mostly however you like. However frameworks are less flexible. There are rules and principles to how code should be architectured with frameworks and React by itself, doesn't do this.

### How else does React improve efficiency?

As well as providing developers with a library of pre-built code, React improves efficiency by manipulating the virtual DOM first.

### What is DOM manipulation?

The DOM is an acronym for Document Object Model. The DOM is like a blueprint or tree of a website. It lists the elements on a website and how they are linked together.

Manipulating the DOM means changing the structure and look of a website. It is like changing a "Login" button to "Logout" when a user signs in.

### How does using a virtual DOM more efficient?

The virtual DOM creates a copy of the original DOM. When changes are made to the webpage, the virtual DOM changes first and is compared with the original DOM. Then only the states/components that are different, are the ones that change on the original DOM. For example:

Let's see what happens withOUT the virtual DOM first.

Imagine you want to mix the pancake batter yourself, and you have a list of ingredients for your recipe printed on a personal blog. But now you want to add chocolate chips to the recipe. Adding one ingredient when using just the original DOM will re-render the whole list.

However, using React means the virtual DOM will only update the one added ingredient, compare this with the original DOM and the original DOM will then only update the one ingredient rather than the full list. Also the virtual DOM can update a lot faster than the original DOM.
