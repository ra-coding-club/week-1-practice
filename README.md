# Week 1 Practice

**Read [What’s in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML) and answer the following questions below.**

### Questions

Example Question: The ______ of an HTML document is the part that is not displayed in the web browser when the page is loaded. 

1. What is the head's job?

2. **Quote the article** to explain the difference between the `<title>` element and the `<h1>` element. 

3. You can put elements inside other elements too — this is called _______.

4. Write the code for specifying your document's character encoding.

5. Many `<meta>` elements include `name` and `content` attributes. Explain what those two attributes are.

6. The humble ______, which has been around for many years, was the first icon of this type, a 16 x 16 pixel icon used in multiple places.

7. The ______ element always goes inside the head of your document.

8. *True or False?* - The `<script>` element does not have to go in the head. *Explain why or why not by quoting the article.*

9. What four-letter attribute sets the primary language of the document?

10. *True or False?* - There's a lot more you can do in here, but an exhaustive tour would be boring and confusing at this stage, and we just wanted to give you an idea of the most common things you'll find in there for now!

**Read [HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals) and answer the following questions below.**

11. Why do we need semantics?

12. **Quote two sentences of the article** and explain the difference between ordered and unordered lists.

13. Summarize in complete sentences the **emphasis and importance** section of the article.

**Read [Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure) and answer the following questions below.**

14. Define the **5** basic sections of a document.

15. Explain non-semantic wrappers.

### Answers
Type your answers here:

Example Answer: *head*

1. The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page <title>, links to CSS (if you choose to style your HTML content with CSS), links to custom favicons, and other metadata (data about the HTML, such as the author, and important keywords that describe the document.)

2. We've already seen the `<title>` element in action — this can be used to add a title to the document. This however can get confused with the `<h1>` element, which is used to add a top level heading to your body content — this is also sometimes referred to as the page title. But they are different things! The `<h1>` element appears on the page when loaded in the browser — generally this should be used once per page, to mark up the title of your page content (the story title, or news headline, or whatever is appropriate to your usage.)
The `<title>` element is metadata that represents the title of the overall HTML document (not the document's content.)

3. Nesting

4. `<meta charset="utf-8">`

5. `name` specifies the type of meta element it is; what type of information it contains. `content` specifies the actual meta content.

6. favicon

7. `<link>`

8. True. The `<script>` element does not have to go in the head; in fact, often it is better to put it at the bottom of the document body (just before the closing `</body>` tag), to make sure that all the HTML content has been read by the browser before it tries to apply JavaScript to it (if JavaScript tries to access an element that doesn't yet exist, the browser will throw an error.)

9. lang

10. True!

11. One of HTML's main jobs is to give text structure and meaning (also known as semantics) so that a browser can display it correctly.

12. Unordered lists are used to mark up lists of items for which the order of the items doesn't matter. Ordered lists are lists in which the order of the items does matter.

13. In human language, we often emphasise certain words to alter the meaning of a sentence, and we often want to mark certain words as important or different in some way. HTML provides various semantic elements to allow us to mark up textual content with such effects.

14. (1) Header, (2) navigation bar, (3) main content, (4) sidebar, (5) footer.

15. Sometimes you'll come across a situation where you can't find an ideal semantic element to group some items together or wrap some content. Sometimes you might want to just group a set of elements together to affect them all as a single entity with some CSS or JavaScript. For cases like these, HTML provides the `<div>` and `<span>` elements. You should use these preferably with a suitable class attribute, to provide some kind of label for them so they can be easily targeted.

**Copyright &copy; 2018 Riyaad Azad. Free to copy and distribute as per the [official license on GitHub](https://github.com/ra-coding-club/coding-club/blob/master/LICENSE). All other rights reserved.** 
