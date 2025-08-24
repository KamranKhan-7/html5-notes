# HTML `<hr>` and `<pre>` Tags

---

## `<hr>` Tag (Horizontal Rule)

### 📌 Notes
- Inserts a horizontal line (thematic break).
- Self-closing tag → no closing `</hr>` needed.
- Commonly used to separate content.

### ✅ Syntax
`<hr>`
✅ Example
`<p>Paragraph One</p>`
`<hr>`
`<p>Paragraph Two</p>`
✅ Attributes (Deprecated in HTML5)
| Attribute | Description                     | Example                |
|-----------|---------------------------------|------------------------|
| `color`   | Line color                      | `<hr color="red">`     |
| `size`    | Line thickness                  | `<hr size="5">`        |
| `width`   | Line width (px or %)            | `<hr width="50%">`     |
| `align`   | Alignment (left, right, center) | `<hr align="center">`  |
| `noshade` | Removes 3D shading              | `<hr noshade>`         |


✔️ Modern way (CSS):
`<hr style="border: 2px solid blue; width: 70%;">`
<pre> Tag (Preformatted Text)
📌 Notes
Preserves spaces, tabs, and line breaks.

Displays text in a monospaced (fixed-width) font.

Useful for showing code or text exactly as written.

✅ Syntax

<pre>
  This text
    keeps spacing
  and line breaks
</pre>
✅ Example


<pre>
Line 1
    Line 2 (indented)
Line 3
</pre>
✅ Output (in browser)

Line 1
    Line 2 (indented)
Line 3
### self closing tags
| Tags       | Function / Use |
|-----------|----------------|
| `<area>`  | Defines a clickable area inside an image map. |
| `<base>`  | Specifies the base URL/target for all relative URLs in a document. |
| `<br>`    | Inserts a single line break. |
| `<col>`   | Specifies column properties for each column within a `<colgroup>`. |
| `<embed>` | Embeds external content (like multimedia, plugins). |
| `<hr>`    | Represents a thematic break (horizontal line) between content. |
| `<img>`   | Embeds an image into the page. |
| `<input>` | Defines an input control (text box, checkbox, radio, etc.). |
| `<link>`  | Defines the relationship between the document and external resources (like CSS). |
| `<meta>`  | Provides metadata about the document (character set, description, keywords). |
| `<source>`| Specifies multiple media resources for `<audio>` or `<video>`. |
| `<track>` | Specifies text tracks (subtitles, captions) for `<video>` or `<audio>`. |
| `<wbr>`   | Suggests a line break opportunity inside text. |
