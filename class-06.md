1. Understanding the problem domain is the hardest part of programming
   - Programming is easy if you understand the problem domain
   - if you want to make understanding easier, you can make the prodlem domain easier or get better at understanding the prodlem domain
   - you can often make the problem domain eeasier by cutting out cases and narrowing your focus to a particular part of the problem
   - it is easy to fall into a trap of thinking you understand enough of the problem to get started coding
2. Object Litterals
   - literal notation is the easiest and most popular way to create objects
   - you access properties or methods of an object using a dot notaion
   - you can access properties using square brackets
3. Document Object Model 
   - Methods that find elements in the dom tree are called dom queries
   - when you need to work with an element more than once, you should use a variable to store the result of this query
   - when people talk about storing elements un variables, they are really talking about storing the location of themelement(s) within the domtree in a variable
   - getElementById and querrySelector both can seach an entire documant and return individual elements
   - there are two ways to select an element from a nodeList, the item method and array syntax
   - array syntax is prefered over the item method because it is faster 
     before selecting a node from a nodeList, check that it contains nodes
   - when you have a nodeList, you can loop through each node in the collection and apply the same statement to each
   - there are two very differnt approaches to adding and removing cintent from a dom tree, the innerHTML and dom manipulation
   - dom manipulation easily targets individual nodes in the dom tree, whereas innerHTML is better suited to updating emtire fragments
   - once you have an element node, you can use other properties and methods on that element node to access and change its attributes
