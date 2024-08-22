## Project Content
#### The project contains configuring a Spring Security application with custom settings beyond the default configurations.
#### The process of using bcrypt to enhance security by running the hashing algorithm.
#### The necessity of updating both user registration and validation processes to incorporate bcrypt, ensuring passwords are encrypted when stored and correctly verified during login.
#### The use of JWT eliminates the need for maintaining server-side sessions, as the token contains all the necessary information for authentication.
#### Implementing JWT in a Spring Boot project involves configuring multiple classes and interfaces for secure token-based authentication.
#### Generating a token with specific claims ensures that each token is unique and contains relevant information about the user, such as the subject (e.g., username), issue date, and expiry, enhancing security and providing necessary user details for the application.
#### The process of validating the token involves decoding it, checking for expiration, and ensuring it corresponds to a valid user in the database.
