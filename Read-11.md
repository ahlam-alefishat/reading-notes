# Read-11

# Watch EJS tutorial from WalkThroughCode on YouTube, Videos 1-5
*video 2- Getting Started*

- npm init -y (for package.json)
- npm install --save express body-parser cors ejs
- terminal --> node server.js

*video 3- Injecting values into the views*

- response render actually take three parameters
* View, which is the string of file name.
* Object/data, local variable.
 * callback
-  * `<h1>Hello <%= foo %></h1>`
-  * `<img src="<%= foo %>" alt="">`
-  * `<a href="/<%= foo.id %>/destroy"></a>`

*video 4- For Loops and Arrays*

*video 5- If/Else Statement*

## Google Books API Docs
- This request has a single required parameter:
- * q Search for volumes that contain this text string.
- * intitle: Returns results where the text following this keyword is found in the title.
- * inauthor: Returns results where the text following this keyword is found in the author.
- * inpublisher: Returns results where the text following this keyword is found in the publisher.
- * subject: Returns results where the text following this keyword is listed in the category list of the volume.
- * isbn: Returns results where the text following this keyword is the ISBN number.
- * lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
- * oclc: Returns results where the text following this keyword is the Online Computer Library Center number.

## Filtering
- You can use the filter parameter to restrict the returned results further by setting it the to one of the following values:
- * partial: Returns results where at least parts of the text are previewable.
- * full: Only returns results where all of the text is viewable.
- * free-ebooks: Only returns results that are free Google eBooks.
- * paid-ebooks: Only returns results that are Google eBooks with a price.
- * ebooks: Only returns results that are Google eBooks, paid or free.

## Print Type
- * all: Does not restrict by print type (default).
- * books: Returns only results that are books.
- * magazines: Returns results that are magazines.

## Projection
* full: Returns all Volume fields.
* lite: Returns only certain fields.

## Sorting
* relevance: Returns results in order of the relevance of search terms (this is the default).
* newest: Returns results in order of most recently to least recently published.