# fs-cat-app

HTML stands for HyperText Markup Language and it represents the content and structure of a web page.

In this workshop, you will learn how to work with basic HTML elements such as headings, paragraphs, images, links, and lists.

Step 1
In this workshop, you will learn how to work with basic HTML
elements like headings, paragraphs, and lists by building a
cat photo app.

        The first element you will learn about is the h1 element.
        The h1 element is a heading element and is used for the main
        heading of a webpage.

        Example Code
        <h1>This is a main heading</h1>
        Add an h1 element with the text of CatPhotoApp and watch the
        change in the browser preview.

        When you are done, press the "Check Your Code" button to see
        if it's correct.

Step 2
The h1 through h6 heading elements are used to signify
the importance of content below them. The lower the number,
the higher the importance, so h2 elements have less
importance than h1 elements.

          Example Code
          <h1>most important heading element</h1>
          <h2>second most important heading element</h2>
          <h3>third most important heading element</h3>
          <h4>fourth most important heading element</h4>
          <h5>fifth most important heading element</h5>
          <h6>least important heading element</h6>
          Only use one h1 element per page and place lower-importance
          headings below higher-importance headings.

          Below the h1 element, add an h2 element with this text:

          Cat Photos

Step 3
The p element is used to create a paragraph of text on websites.
Create a p element below your h2 element and give it the following
text:

          Everyone loves cute cats online!


Step 4
Commenting allows you to leave messages without affecting the browser
display. It also allows you to make code inactive. A comment in HTML
starts with, contains any number of lines of text, and ends with.

          Here is an example of a comment with the TODO: Remove h1:

          Example Code
          TODO: Remove h1
          Add a comment above the p element with this text:

          TODO: Add link to cat photos

Step 5
HTML5 has some elements that identify different content areas.
These elements make your HTML easier to read and help with
Search Engine Optimization (SEO) and accessibility.

          The main element is used to represent the main content of the body
          of an HTML document. Content inside the main element should be unique
          to the document and should not be repeated in other parts of the document.

          Example Code
          <main>
            <h1>Most important content of the document</h1>
            <p>Some more important content...</p>
          </main>
          Identify the main section of this page by adding a <main> opening tag before
          the h1 element, and a </main> closing tag after the p element.


Step 6
In the previous step, you put the h1, h2, comment, and p elements inside the main element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.

Here is an example of nesting and indentation:

Example Code

<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
The h1 element, h2 element and the comment are indented two spaces more than the main element in the code below. Use the space bar on your keyboard to add two more spaces in front of the p element so that it is indented properly as well.

Step 7
You can add images to your website by using the img element. img elements have an opening tag without a closing tag. An element without a closing tag is known as a void element.

Add an img element below the p element. At this point, no image will show up in the browser.

Step 8
HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).

Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

Example Code
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">
Inside the existing img element, add a src attribute with this URL:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

Step 9
All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

Here is an example of an img element with an alt attribute:

Example Code
<img src="cat.jpg" alt="A cat">
Inside the img element, add an alt attribute with this text:

A cute orange cat lying on its back

Step 10
You can link to another page with the anchor (a) element.

Here is an example linking to https://www.freecodecamp.org:

Example Code
<a href="https://www.freecodecamp.org"></a>
Add an anchor element after the paragraph that links to https://freecatphotoapp.com. At this point, the link won't show up in the preview.

Step 11
A link's text must be placed between the opening and closing tags of an anchor (a) element.

Here is an example of a link with the text click here to go to freeCodeCamp.org:

Example Code
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
Add the anchor text cat photos to the anchor element. This will become the link's text.

Step 12
Add the words See more  before the anchor element and  in our gallery after the anchor element.

Step 13
Add p tags to turn See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery. into a paragraph.

Step 14
Turn the existing text cute cats into an anchor element that links to:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg

Step 15
To open links in a new tab, you can use the target attribute on the anchor (a) element.

The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.

Here is the basic syntax for an a element with a target attribute:

Example Code
<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
Add a target attribute with the value _blank to the anchor (a) element's opening tag, so that the link opens in a new tab.

Step 16
Now that you have added the link you can remove the comment.

Step 17
In previous steps, you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.

Here is an example of turning an image into a link:

Example Code
<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>
Turn the image into a link by surrounding it with necessary element tags. Use https://freecatphotoapp.com as the anchor's href attribute value.

Step 18
Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.

The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

Example Code
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
Take your h2 element, two p elements, and anchor (a) element and nest them in a section element.

Step 19
It is time to add a new section. Add a second section element below the existing section element.

Step 20
Within the second section element, add a new h2 element with the text Cat Lists.

Step 21
When you add a lower-rank heading element to the page, it's implied that you're starting a new subsection.

After the last h2 element of the second section element, add an h3 element with this text:

Things cats love:

Step 22
To create an unordered list of items, you can use the ul element.

After the h3 element with the Things cats love: text, add an unordered list (ul) element. Note that nothing will be displayed at this point.

Step 23
The li element is used to create a list item in an ordered or unordered list.

Here is an example of list items in an unordered list:

Example Code
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
Within the ul element nest three list items to display three things cats love:

catnip

laser pointers

lasagna

Step 24
After the unordered list, add a new image with a src attribute value set to:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg

And its alt attribute value to:

A slice of lasagna on a plate.

Step 25
The figure element represents self-contained content and will allow you to associate an image with a caption.

Nest the image you just added within a figure element.

Step 26
A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.

Here is an example of a figcaption element with the caption of A cute cat:

Example Code
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
After the image nested in the figure element, add a figcaption element with text set to:

Cats love lasagna.

Step 27
To place emphasis on a specific word or phrase, you can use the em element.

Emphasize the word love in the figcaption element by wrapping it in an emphasis em element.

Step 28 
After the figure element, add another h3 element with the text:

Top 3 things cats hate:

Step 29
The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.

Below the h3 element, add an ordered list with these three list items:

flea treatment thunder other cats

Step 30
After the ordered list, add another figure element.

Step 31
Inside the figure element you just added, nest an img element with a src attribute set to https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg.

tep 32
To improve the accessibility of the image you added, add an alt attribute with the text:

Five cats looking around a field.

Step 33
After the last img element, add a figcaption element with the text Cats hate other cats.

Step 34
The strong element is used to indicate that some text is of strong importance or urgent.

In the figcaption you just added, indicate that hate is of strong importance by wrapping it in a strong element.

Step 35
The footer element is used to define a footer for a document or section. A footer typically contains information about the author of the document, copyright data, links to terms of use, contact information, and more.

After the main element, add a footer element.

Step 36
Nest a p element with the text No Copyright - freeCodeCamp.org within the footer element.

Step 37
Turn the existing freeCodeCamp.org text into a link by enclosing it in an anchor (a) element. The href attribute should be set to https://www.freecodecamp.org.

Step 38
Notice that everything you've added to the page so far is inside the body element. All page content elements that should be rendered to the page go inside the body element. However, other important information goes inside the head element.

The head element is used to contain metadata about the document, such as its title, links to stylesheets, and scripts. Metadata is information about the page that isn't displayed directly on the page.

Add a head element above the body element.

Step 39
The title element determines what browsers show in the title bar or tab for the page.

Add a title element within the head element using the text below:

CatPhotoApp

Step 40
Notice that the entire contents of the page are nested within an html element. The html element is the root element of an HTML page and wraps all content on the page.

You can also specify the language of your page by adding the lang attribute to the html element.

Add the lang attribute with the value en to the opening html tag to specify that the language of the page is English.

Step 41
All pages should begin with <!DOCTYPE html>. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.

<!DOCTYPE html> tells browsers that the document is an HTML5 document which is the latest version of HTML.

Add this declaration as the first line of the code.

Step 42 Passed
You can set browser behavior by adding meta elements in the head. Here's an example:

Example Code
<meta attribute="value">
Inside the head element, nest a meta element with a charset attribute set to the value of utf-8. This tells the browser how to encode characters for the page.

Note that the meta element is a void element.

With that last change, you have completed the Cat Photo App workshop. Congratulations!
