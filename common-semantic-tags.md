# Doc: Common HTML Semantics
* `<header>`: Defines the header section of a page or section
* `<nav>`: Defines a navigation section
* `<main>`: Defines the main content of a page or section
* `<section>`: Defines a section of content within a document
* `<article>`: Defines an independent piece of content within a document, such as a blog post or news article
* `<aside>`: Defines content that is tangentially related to the main content, such as a sidebar or a callout box
* `<footer>`: Defines the footer section of a page or section

* `<h1>` to `<h6>`: Defines heading levels 1 through 6
* `<p>`: Defines a paragraph of text
* `<ul>`: Defines an unordered list
* `<ol>`: Defines an ordered list
* `<li>`: Defines a list item
* `<figure>`: Defines a figure or illustration, along with an optional caption using the <figcaption> element
* `<time>`: Defines a date or time
* `<address>`: Defines contact information for the author or owner of a document

<br>

## < header >
```
<header>
  <h1>Welcome to My Website</h1>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>
```

<br>

## < main >
```
<main>
  <h2>About Us</h2>
  <p>We are a small company that specializes in creating beautiful and functional websites for our clients.</p>
  
  <h3>Our Services</h3>
  <ul>
    <li>Web Design</li>
    <li>Web Development</li>
    <li>Search Engine Optimization</li>
  </ul>
</main>
```

<br>

## < section >
```
<section>
  <h2>Our Team</h2>
  <ul>
    <li>
      <h3>Ada Lovelace</h3>
      <p>Sr. Engineer</p>
    </li>
    <li>
      <h3>Mr. Anderson</h3>
      <p>Web Developer</p>
    </li>
  </ul>
</section>
```

<br>

## < figure >
```
<figure>
  <img src="my-image.jpg" alt="A beautiful image" />
  <figcaption>This is a beautiful image</figcaption>
</figure>
```    

<br>

## < article >
```
<article>
  <h2>10 Tips for Creating a Great Website</h2>
  <p>Creating a great website can be a daunting task, but with these 10 tips, you'll be on your way to success in no time!</p>
  <ol>
    <li>Define your goals and target audience</li>
    <li>Make your site mobile-friendly</li>
    <li>Make sure your site is accessible</li>
  </ol>
</article>
```

<br>

## < time >
```
<p>The event will take place on <time datetime="2023-06-15T18:00">June 15, 2023 at 6:00pm</time>.</p>
```

<br>

## < footer >
```
<footer>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
  <p><small>&copy; 2023 My Website. All rights reserved.</small></p>
</footer>
```