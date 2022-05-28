## Explaination of the principle of Oauth2.0

You can click on the [Blog Home](./index.md) to browser my blogs and find more interesting 
content.
If there are any issues or suggestions, please feel free to reach out to me or simply submit a merge request on 
[GitHub Link](https://lorenzolou.github.io/blog/)

## What's OAuth?

[link test](./LinkTest.md)

OAuth is a protocol that designed to protect the user who wanna share their data to third part application or systems.
OAuth 2.0 is subsequent version of OAuth 1.0, mostly we use OAuth 2.0 nowadays.


### Sample

Let's say when we're going to log in YOUTUBE by using the account of GOOGLE

#### Terms
In this case some here are the professional introduction of terms we may use.
* Resource Server: In this case, YOUTUBE is going to get the username, profile, avatar from GOOGLE, so we call GOOGLE 
service which stored this kind of user information as Resource Server 
* Resource Owner: Denotes the user here.
* Client: Denotes YOUTUBE here.
* Authorization Server: In this case, it should be the server of GOOGLE also.(we just differentiate Authorization Server
with Resource Service logically, they can be provided by a same server)
* Useragent: The browser you use when you're browsing the YOUTUBE videos.

base on authorization code mode
//todo [Image](src)

if your application is based on frontend and backend separation architecture, then every request you send should involve
the token.

For more details
see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
.

### AUTH MODE

Here we just introduce two commonly used modes: Authorization Code Mode and Client Credentials

#### Authorization Code Mode

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/)
or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

#### Client Credentials


