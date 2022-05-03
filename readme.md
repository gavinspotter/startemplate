MERN (mongodb, express, react, node) template

a lot of great things in this template whether your working for a client or you wanna jump right in read some docs and start developing

Server side off the top of my head (mongodb, express, node)

express ... make requests with npmjs library's via latent calls

stripe ... LOVE, the stripe package, jumped in went from onboarding via the stripe site to the custom stripe api.

aws-sdk ... I use this to access some great AWS features like SES (email), Workmail(email), and S3 (files)

body-parser ... allows for form data

form-data ... body-parser was deprecated and this is two lines of code so I put it in to sieve any potential hazards.

fs ... node package, no download necessary. fs means file system, great for maneuvering your program.

mongoose ... schema's, server starter, easy to pick api. I jumped in the api and it was like I was reading from the dictionary.

socket-io ... adds a great listening aspect applications.

nodemon ... Keeps the server running be sure to exclude the react client folder.

nodemailer ... I use this with amazon SES and Amazon workmail, a little bit of IT involved when incorporating those external programs.

prerender-node ... SEO prerender tags like open graph tags.

uuid ... random ids.

geoip-lite ... This is so we can bounce people who for example accidentally submit a form to many times. Maybe we want to see viewers and log it to the client. Regulate comments and likes without having to establish authentication.

axios ... "Gav, why axios when we have express?" "Well theres a lot company's out there they write api's their not packaged to deal with express like one would use stripe which has a great api btw. So ya know we gotta get the token submit form data."

client side (react, node) of the top of my head

react-icons

react-dom

react-router-dom

react

socket-io-client

react-form-hook

theres a lot of basic react bcrypt jsonwebtoken stuff, I put a bunch of semantic auth stuff, whether its auth for a customer, auth for an employee, auth for a ceo, etc.
