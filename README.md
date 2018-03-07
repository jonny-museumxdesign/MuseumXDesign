### MuseumXDesign

### A little bit about me

I'm not a computer scientist, I learnt to code by teaching myself through experimenting and tinkering.
I was recently in your shoes and want to show you that it's easy to get started and anyone can give it a go!

### A little bit about you

Do you have any coding experience?

### Session plan

What we are going to do today
 - Get you started on the world's biggest network of coders
 - Launch your own web page live on the internet
 - Make your page unique by playing with code in HTML and CSS languages
 - Enable museum visitors to access your page when they get to your chosen gallery or object

## Presenting content on the web

**content/format**
 - What do we want people to get out of our project?
  - Do we want to invoke emotion, inform, inspire etc?
 - What kind of content do we need to achieve these things?
  - A compelling title, copy, images etc?

**Wireframes**

**Distribution**
 - Pre Web
 
 <!-- Pretend we're back in 1970 or date before the web existed. How might we distribute the content we've sketched out? Stick it to your fridge, that may access a small audience. Pin in to a notice board, local area can access a wider audience. You could all do this, you know what tools you need to achieve this, pens, paper, pins, maybe a printer. -->
 
 - Web
 
 <!-- Now we have the web, which gives us the potential to access billions of people. The tools you need to get this done are much less obvious and not until recently were taught at school. So, lets start taking a quick look at the tools needed to create a website. -->

## Anatomy of the web

- Browser
- Server
- HTTP
- HTML
- CSS

Chrome developer tools

## Getting a page live

### Github :octocat:

- Collaboration
- Community
- Sharing
- Hosting

<!-- - Demonstrate the Facebook etc. Github repo, show the collaboration and sharing aspects.
- Everyone starts their first repo using the Github Pages automatic generator to get a generic page live. Relate this back to the anatomy i.e. where is the server, what is the starting code. -->

## Customising code

#### HTML basics

HTML is a *markup* language, which you use to *format your content*.

Essentially, you wrap content inside bits of code called tags.

`<tag> content </tag>`

The bits of code inside angle brackets `<` and `>` are instructions for the computer:

* They describe the content they wrap
* Define where it starts `<tag>`
* Define where it ends `</tag>`

For example, this is how you wrap a paragraph of text in `p` tags:

`<p> This is a paragraph. </p>`

`p` stands for *paragraph*, of course.

![](/assets/images/HTML_doc_setup.jpg)

![](/assets/images/headings.jpg)

![](/assets/images/attributes.jpg)

You can add **hyperlinks** to our content using the `a` element.

```html
<a href="http://example.com"> the clickable text </a>
```

`a` is for *anchor* :anchor:

```html
<p>To find out more visit this <a href="http://example.com">Wikipedia</a> page.</p>
```

#### CSS basics

You use CSS to style HTML.

CSS looks and works differently than HTML.

```css
selector
{
	property: value;
	property: value;
}
```

The part before the curly brackets `{` and `}` is the **selector**. This ***selects* the element** from your HTML document.

In CSS you can select multiple HTML elements in one go.

For example, to select all paragraphs you can write

```css
p
{
	/* your styles for paragraph here */
}
```

CSS **properties** define how HTML elements are displayed.

![](assets/images/css_layout.jpg)

The first bit is the property name, eg `color`, and the second bit is the value, eg `green`. They are separated by a `:` colon, and you MUST end each line of CSS with a `;` semicolon (for real, otherwise your browser will choke).

For example ...

```css
p
{
	color: green;
}
```

... will turn *every* paragraph in your HTML green.

<!-- - JSBin -->
<!-- - Paste generic code into JSBin and edit -->
<!-- - Get all learners to a first, basic level of customisation and commit the changes in the GitHub repository. Note the changes to the public page. -->

## Free play

- Now it is time to experiment!
- Fonts, images, video embed, colours, Facebook like buttons are all a great place to start!
- Help each other out!

## Linking the digital with the physical

![lighthouse](/assets/images/lighthouse.jpg)

![NFC](/assets/images/nfc_smarttags.jpg)

![QR](/assets/images/qr_reader.jpg)

## Bug fixing
