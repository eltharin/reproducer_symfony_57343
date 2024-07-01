juste have to make a composer install and serve it,
If you go to https://127.0.0.1:8000/test you will be redirect to /login (I don't agree with that but it's another discussion)
if you log with user@fr.fr / password and go to /test you are still redirected to /login
if you change InvalidCsrfTokenException extends BadRequestHttpException  instaed of AuthenticationException you have an error page with Invalid CSRF Token
