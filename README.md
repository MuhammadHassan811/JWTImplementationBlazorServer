# JWTImplementationBlazorServer
This is a basic application for jwt token generation using blazor server app.



This is a basic Blazor Server application implementing JWT (JSON Web Token) authentication. In this application:

A login page is implemented where users can input their credentials.
Upon clicking the login button, a JWT token is generated.
After generating the token, the application navigates to the home page.
Here’s a step-by-step breakdown of how the JWT authentication is implemented:

JWT Setup: The TokenService class is used to generate JWT tokens. This class is configured with a secret key and issuer, which are stored in the appsettings.json file.

Login Page: The login page includes a button that, when clicked, triggers the Login method. This method uses the TokenService to generate a JWT token for the user and then redirects to the home page.

Navigation: After generating the token, the application uses Blazor's NavigationManager to redirect the user to the home page.
