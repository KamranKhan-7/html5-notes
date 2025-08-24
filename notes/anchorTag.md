## Anchor (<a>) Tag in HTML5  

The `<a>` tag is used to create hyperlinks.  
It can link to web pages, sections in the same page, files, emails, phone numbers, or external resources.  

Basic Syntax:
`<a href="URL">Link Text</a>`

| Attribute  | Meaning                                                                                        | Example                                                                             | When to Use                                                                                               |
| ---------- | ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| `href`     | The **destination URL** or resource to link to. Can be a page, file, email, phone, or section. | `<a href="about.html">About Us</a>`                                                 | Always required for a working link. Without it, `<a>` can be used as a placeholder or JavaScript trigger. |
| `target`   | Defines **where to open the link** (`_self`, `_blank`, `_parent`, `_top`, or frame name).      | `<a href="page.html" target="_blank">Open in New Tab</a>`                           | Use `_blank` for external sites, `_self` (default) for internal navigation.                               |
| `download` | Makes the link **download a file instead of opening it**.                                      | `<a href="resume.pdf" download>Download Resume</a>`                                 | When linking to files (PDF, images, docs, etc.).                                                          |
| `rel`      | Defines **relationship between current page and linked page**.                                 | `<a href="https://example.com" target="_blank" rel="noopener noreferrer">Visit</a>` | For SEO (`nofollow`) and **security** (when using `_blank`).                                              |
| `title`    | Adds a **tooltip** when user hovers over the link.                                             | `<a href="page.html" title="Learn more about us">About Us</a>`                      | Use when you want to give **extra info** about the link.                                                  |
| `type`     | Specifies the **MIME type** of the linked resource.                                            | `<a href="video.mp4" type="video/mp4">Video</a>`                                    | Rarely used, helpful for specifying file formats.                                                         |
