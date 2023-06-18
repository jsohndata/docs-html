# Document Object Model (DOM)
Strucutral reprensentation of the elements in  a document and their relationships. It represents the structure of a document as a tree-like object, where each part of the document is represented by a node in the tree. The DOM provides a way to interact with these elements and manipulate them using code. 

## When document is loaded
The Browser reads the HTML code and creates a `DOM tree` that `represents the structure of the page`.

## Elements as nodes
Each HTML element, such as headings, paragraphs, images, and buttons, becomes a `node` in the DOM tree. These `nodes can have relationships with each other`, like parent-child or sibling relationships.

## Nodes and properties
Each node has `properties` that you can `access and modify`. For example, you can change the text inside a paragraph, update an image source, or add a CSS class to an element.

## Traversing the tree
You can navigate through the DOM tree by moving from one node to another. For example, you can access the parent of a node, get a list of its children, or find specific elements based on their attributes or position in the tree.

## Event handling
The DOM allows you to listen for and respond to events triggered by user interactions, like clicks, mouse movements, or keyboard inputs. You can attach event listeners to nodes and specify code that should run when the event occurs.