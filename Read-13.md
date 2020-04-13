# Read-13
## Sending Form Data
Client/server architecture
- At it's most basic, the web uses a client/server architecture that can be summarized as follows.
- a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol.
- The server answers the request using the same protocol.
On the client side: defining how to send the data
- The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button.
- The two most important attributes are action and method.
your form data will be shown as follows in the Chrome Network tab. After submitting the form:
1. Open the developer tools.
2. Select "Network"
3. Select "All"
4. Select "foo.com" in the "Name" tab
5. Select "Headers"
If you want to send files, you need to take three extra steps:
- Set the method attribute to POST because file content can't be put inside URL parameters.
- Set the value of enctype to multipart/form-data because the data will be split into multiple parts, one for each file plus one for the text data included in the form body (if text is also entered into the form).
- Include one or more controls to allow your users to select the file(s) that will be uploaded.

## Security Issues
- There are a few rules to keep in mind. The most important rule is: never ever trust your users, including yourself; even a trusted user could have been hijacked.
- All data that comes to your server must be checked and sanitized. Always. No exception.
- Escape potentially dangerous characters. all server-side languages have functions for this. Things to watch out for are character sequences that look like executable code (such as JavaScript or SQL commands).
- Limit the incoming amount of data to allow only what’s necessary.
- Sandbox uploaded files. Store them on a different server and allow access to the file only through a different subdomain or even better through a completely different domain.