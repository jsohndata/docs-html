# Starter HTML

## 1. Structure: Open and Close Tag
```
<tagOpen>Content </tagClose>
```

### Sample
```
<h1>Header 1</h1>
<h2>Header2 Sub</h2>
<h3>Header 3 Sub Sub</h3>
<p>Paragraph</p>
```

<br>

## 2. Structure: Self Closing Tag
```
<tagSelfClosing />
````

### Sample
```
<br />: Break
<img />: Image
<hr />: Horizontal Rule
```

<br>

## 3. Tags Covered Today
`<head>`: Think of this as the "behind-the-scenes" section of your HTML document. It contains information about the document, such as the title, character encoding, and other metadata. This section is not directly visible on the webpage itself.

`<body>`: Think of this as the main "stage" of your webpage. It contains all the visible content that users see when they visit your website, such as text, images, videos, links, and more. Basically, anything you want to display on your webpage goes inside the <body>.

`<h1>`: Header 1. Highest level of heading on a webpage. It is typically used to indicate the main heading or the title of the page. It is recommended to have only one h1 tag per page (it helps search engines and users understand the primary topic or purpose of the content.)

`<h2>`: Header 2. This represents a secondary level heading. It is commonly used to divide the content into sections or subsections. Multiple h2 tags can be used within a page, and they are typically used to introduce different topics or subtopics.

`<h3> - <h6>`: These tags represents a subheading, which is nested under the h2 heading. It is used to provide further organization and structure within a section or subsection of a webpage. These tags are often employed when there is a need to break down content into smaller, more specific divisions.

`<p> </p>`: Paragraph

`<br />`: Break tag

`<strong> </strong>`: Strong (visually bold)

`<em> </em>`: Emphasize (visually italic)

`<small> <small>`: Small (visuall small)

`<ol> </ol>`: Ordered List

`<ul> </ul>`: Unordered List

`<li> </li>`: Line

`<a> </a>`: Anchor

`<img>`: Image



<br>

### 3.1 Attributes
Thesea are used to provide additional information or modify the behavior of an HTML element. Attributes are added to the opening tag of an HTML element and consist of a name-value pair.

### 3.1.1 A Tag
`href=URL` Hypertext Reference

`taget=_blank` Target window

<br>

### 3.1.2 Image
`src=URL`: Source

`alt='descripion of the image`: Alternative Tag

`loading="lazy"`: Lazy Load

<br>

## 4.0 HTML character entities
They are used to represent special characters in HTML code. 

`&lt;`: less-than symbol <

`&gt;`: greater-than symbol >

`&copy;`: copyright



<br>

## 6.0 Bonus: Detail
```
<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>
```