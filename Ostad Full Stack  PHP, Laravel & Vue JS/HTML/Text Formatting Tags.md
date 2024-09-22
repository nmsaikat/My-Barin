
#### ``<h1>`` to ``<h6>:``
- **These tags are used for creating headings.``<h1>`` represents the most important heading, while ``<h6>`` represents the least important.**

#### ``<p>``
- **Defines a paragraph.**

#### ``<strong>``
- **Makes text bold.**

#### ``<em>``
- **Italicises text, indicating emphasis.**

#### ``<small>``
- **Decreases the size of the text.**

#### ``<mark>``
- **Highlights text.**

#### ``<sub>``
- **Creates subscript text.**

#### ``<sup>``
- **Creates superscript text.**

#### ``<ins>``
- **Represents inserted text.**

#### ``<del>``
- **Represents deleted text.**

#### ``<code>``
- **Displays its contents styled in a fashion intended to indicate that the text is a short fragment of computer code.**
#### ``<samp>``
- **Used to enclose inline text which represents sample (or quoted) output from a computer program.**
#### ``<blockquote>``
- **Represents a section that is quoted from another source, and the cite attribute can include the URL of the source.**

#### ``<address>``
- **Indicates that the enclosed HTML provides contact information.**

#### ``<hr>``
- **Inserts a horizontal rule, which defines a thematic break in an HTML page.**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Text Formatting Example</title>
  </head>
  <body>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <p>
      This is a paragraph <strong>with bold text</strong> and
      <em>italic text</em>.
    </p>
    <p>
      This is another paragraph with a <br />
      line break.
    </p>
    <p>
      Here's an example of <small>smaller text</small> and
      <mark>highlighted text</mark>.
    </p>
    <p>You can also use <sub>subscript</sub> and <sup>superscript</sup>.</p>
    <p>
      This is a paragraph with <ins>inserted</ins> text and
      <del>deleted</del> text.
    </p>
    <p>
      Here's some <code>computer code</code> and a
      <samp>sample output</samp> from a computer program.
    </p>
    <p>Quotation: <q>Do not go gentle into that good night.</q></p>
    <blockquote
	cite="https://www.poetryfoundation.org/poems/48979/do-not- go-gentle-into-that-good-night">
      Do not go gentle into that good night, Old age should burn and rave at
      close of day; Rage, rage against the dying of the light.
    </blockquote>
    <p>An address example:</p>
    <address>
      Written by John Doe.<br />
      Visit us at:<br />
      Example.com<br />
      Box 564, Disneyland<br />
      USA
    </address>
    <hr />
    <p>This is a paragraph after a horizontal rule.</p>
  </body>
</html>

```