# 003-getting-started-with-html

## Profile Links : [rahuldutta.bio.link](https://rahuldutta.bio.link)

## [Assignment](./assignment/003-getting-started-with-html.pdf)

### 01.

- [View Live](https://irahuldutta02.github.io/pw-skills-fswd-ja-assignments/003-getting-started-with-html/01/)
- [Source Code](https://github.com/irahuldutta02/pw-skills-fswd-ja-assignments/tree/main/003-getting-started-with-html/01/)

### 02.

The purpose of comments in HTML is to add notes or descriptions within the HTML code that are not displayed by the browser. Comments allow developers to leave explanatory notes for other developers or themselves to understand the structure and logic of the HTML code.

Here is an example of how to use comments in HTML:

```html
<!-- This is a comment in HTML -->

<h1>Hello World</h1>

<!-- This heading tag displays "Hello World" text on the page -->
```

In the above example, the text within the <!-- --> tags is comment text that the browser will ignore when rendering the page. The comments explain the purpose of the heading tag below it.

Comments are especially useful when working with complex web pages and templates to indicate sections of code or leave notes for other developers. They allow adding contextual information without impacting what displays to the end user.

### 03.

- [View Live](https://irahuldutta02.github.io/pw-skills-fswd-ja-assignments/003-getting-started-with-html/03/)
- [Source Code](https://github.com/irahuldutta02/pw-skills-fswd-ja-assignments/tree/main/003-getting-started-with-html/03/)

### 04.

A tag and element in HTML refer to the same thing - they are used to structure and give meaning to content on a webpage.

A HTML element consists of an opening tag, content, and a closing tag like this:

```html
<p>This is a paragraph element</p>
```

Here:

- `<p>` is the opening tag
- `This is a paragraph element` is the content
- `</p>` is the closing tag

The whole structure together is called an element. The tags define what type of content is inside, in this case a paragraph denoted by `<p>`.

Some common HTML elements are:

- `<h1>`: Heading 
- `<p>`: Paragraph
- `<img>`: Image
- `<a>`: Anchor or link
- `<div>`: Division or section 

The name inside the angle brackets is the tag name, and together with the content inside it forms an HTML element. Tags tell the browser how to structure and display the content correctly.

### 05.

The DOCTYPE declaration in HTML is used to tell the browser which version of HTML is being used in the document. It appears at the very beginning of the HTML document, before the <html> tag.

The DOCTYPE declaration refers to the Document Type Definition (DTD) which specifies the rules and syntax for that version of HTML. This allows the browser to render the HTML appropriately.

Here are some common DOCTYPE declarations:

HTML5:

```html
<!DOCTYPE html>
```

HTML 4.01:

```html 
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
```

XHTML 1.0 Strict:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
```

The DOCTYPE declaration is optional in HTML5 but required in older versions like HTML 4.01. It is considered a best practice to always include the DOCTYPE even in HTML5 to ensure proper rendering across different browsers.

So in summary, the DOCTYPE declaration helps the browser properly interpret and render the HTML document based on the HTML version rules.