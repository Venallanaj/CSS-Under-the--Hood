# CSS-Under-the--Hood

Css under the Hood

When we create a webpage is important also to understend how works css not only write code

1. Firstly browser load html file take html code (which are tags, elemnents, BEM, and stuff like this).

2. After that Parse it in HTML chek line by line parsing means taking the html code and then extracting valuable information from it.

3. After it parses the HTMl document, all it stores the code in a DOM (Documnet Object Model). In this stage describes the relaionship throught parents, children, and siblings.

4. Next step is the browser find styleesheet css and loads.

5. After loads Css also Parse like HTML file, but there's a slight difference. The parsing CSS files takes place in the two steps :
   a. The first step is: Resolving the CSS declarations conflicts, and this step is also known as Cascading.
   b.The second step is: Processing final CSS values.

6. After the Resolving the CSS declarations conflicts crea CSS Object Model.

7. In the next step Html DOM (Documnet Object Model) AND CSS ( Object Model) atach bothe DOM to make a render Tree.

8. To render the page browser use visual formating like box-model, position, flexbox to render on screen.

9. This finally step Render a website on our sceens that user can see.

![alt text](https://i.postimg.cc/LsfGJy0j/CSS-underhood-css-interview-questions-edureka-1.png)

How CSS works (Part 2)

The Cascade:
A cascade is a structure or a process that rules out different conflicting rules to decide the ultimate winning rule that will be applied to an element.

The cascade following the four key rules inthe following order of privilege:

** Importance** // has the highest privilege
** Specificity**// has a liitle privilege than that A measure of how specifice a selector is.
** Source Order**// has the finally result of css rules that you have applied
** Inheritance** // We can change the color by targetting the element with a selector, such as this spam
