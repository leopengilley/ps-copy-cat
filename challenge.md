# Graduate Engineering Challenge

There are three different challenges to choose from.
Please **attempt one of them** and be prepared to talk through your solution during your technical interview.
We recommend that you allow two hours for the challenge.
Don't worry if you don't complete the challenge, we're interested in your approach not your completed project.

You can use any programming or markup language for the challenges.


## What we're looking for

- A clear README that explains how to run your code and any assumptions that you have made when building your solution
- Concise, well-documented and maintainable code that solves the problem without over engineering it
- An approach that suits the language(s) that you have chosen for the solution


## The Challenges

### Copy Cat

Taking the screenshot we've included, reproduce the layout for a desktop web browser.
Try to get all the components in the correct place while using semantic markup.
Think about how your markup affects accessibility and how the layout will work on different devices.

### Word Counter

Load the HTML document attached and calculate how many words are in the article.
You should exclude any content that isn't part of the article and any markup used for page layout.
Your solution should be able to check the word count of other HTML documents with similar markup.

### Rad Tunes

Create a HTTP API that lets you query the artist objects in the attached JSON file.
Implement a way to filter the results based on a genre provided in the request.
Return a list of results from the API as JSON with a suitable structure.


---

## Interviewer Notes

The notes below are prompts for discussion.

### All challenges

- Does the README contain usage instructions?
- What assumptions were made and documented?

### Copy Cat (HTML / CSS)

- Does the README say what browsers they tested in?
- Does the layout look correct in a desktop browser?
- Are they using the correct HTML tags for various components?
    - Should have: nav, article, h2, header
    - Could have: aside, figure/figcaption  
    - Should not have: caption (used for tables)
- Is the CSS targeting the semantic elements, classes or ids?
- Are they using SASS / LESS / etc. or perhaps a framework to help?
- Did they build the layout with a modern layout solution like flexbox / grid?
- Ask about responsive design, how would they deal with that? (media queries)

### Word Counter (Scripting)

- Does the README tell you how to install the tooling?
- How are they finding the article within the HTML document?
- What technique are they using the removing the HTML tags within the article?
- Can they load other documents?
- What would be involved in loading the document from a URL instead of a file?
- Are there tests?
- Did they get the right number of words?

### Deep Dive (API)

- Does the README include a sample HTTP call that you can make to test it?
- How is the category name filter implemented?
- Does the JSON have a `data` key or similar
- Are they using proper response codes?


---

## References & Acknowledgements

- Screenshot for Copy Cat is the [When frontend means full stack](https://increment.com/frontend/when-frontend-means-full-stack/) article on Increment
- Soundtrack data for Rad Tunes is from [The Pudding](https://github.com/the-pudding/data/tree/master/skate-music) (MIT License)
- Content for the Word Counter challenge from the [MDN Learning Area](https://github.com/mdn/learning-area/tree/main/html/introduction-to-html/structuring-a-page-of-content-finished) examples (CC0)