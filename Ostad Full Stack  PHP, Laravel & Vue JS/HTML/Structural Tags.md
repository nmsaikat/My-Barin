
#### **``<!DOCTYPE html>:``**
- **Declares the document type**

#### **``<html>:``**
- **The root element of an HTML page.**

#### **``<head>:``**
- **Contains meta-information about the document**

#### **``<body>:``**
- **Contains the contents of the HTML document.**

#### **``<header>:``**
- **Represents introductory content, typically containing one or more heading elements ``( <h1> to <h6> )`` and navigation elements ``( <nav> )``.**

#### **``<nav>:``**
- **Defines a set of navigation links.**

#### **``<main>:``**
- **Specifies the main content of the document.**

#### **``<section>:``**
- **Defines a section in a document, such as a chapter, header, footer, or any other sections of the document.**

#### **``<article>:``**
- **Represents a self-contained composition in a document, page, application, or site.**

#### **``<aside>:``**
- **Used for content that is tangentially related to the content around the ``<aside>`` element.**

#### **``<footer>:``**
- **Represents the footer of a document or section**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Sample Web Page</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="home">
        <h2>Home</h2>
        <p>This is the Home section of the page.</p>
      </section>
      <article id="about">
        <h2>About</h2>
        <p>
          This section contains information about the website or its creator.
        </p>
      </article>
      <aside>
        <h2>News</h2>
        <p>Latest news related to the website or topic.</p>
      </aside>
    </main>
    <footer>
      <p>Contact us: email@example.com</p>
    </footer>
  </body>
</html>
```

