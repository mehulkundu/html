
### What is HTML?

- HTML stands for Hypertext Markup Language and is the language for creating web pages
- It is a markup language and not a programming language
- We 'mark certain things in the code we write which tells the web browser how to structure the web page
- It does not contain any logic like conditionals or branching
- HTML consists of series of elements and each element tells the browser hoe to display the content

### HTML Element
An HTML element is the building block of an HTML document
`<tagname> Content goes here </tagname>`

Nesting of html element is possible
```
<tagname>
  <tagname> content </tagname>
</tagname>
```

### `<strong> and <em>` over `<b> and <i>`?

Though strong and bold are visually same, so is emphasis and italics but **bold and italics do not carry any semantic meaning and not good for search engine or screen reader, so stick to strong and em tag.**

### Block elements vs inline elements

Block Elements - Always starts on a new line and occupies the full width available. e.g. Heading, Paragraph, Division tags. 
Inline Elements - Does not start on a new lien and takes as much space that is necessary. e.g. Inline formatting tags such as `<storng>`, `<em>`, `<sub>`, `<sup>`, `<del>`,  `<mark>` and Span tag etc.

### `<div>` and `<span>` tags

When writing HTML alone the div and span tag has less significance. But usefull when we are applying style in group of element or in group of text. More prominent use while using with CSS.