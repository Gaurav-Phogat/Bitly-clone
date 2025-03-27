-> Front-End side: basic React router file with few routes like login,register,"/", dashboard,about,etc.

-> How I was able to build the front-end is with "npm run build", And I deployed it with Netlify.

-> Back-End side: I used Spring Boot for the backend and it is a bit complex since there were many "many to one" relationships.

-> The many to one relations were. 
       -- Storing every click count date separately for a link.
       -- Storing every link for a user.

-> I used Spring Security, Jwt and BCrypt for the security part.

-> Made three models for the database: User, UrlMapping, ClickEvent.

-> The controllers are used for handling direct api calls.

-> the service handles what the controller needs.

-> And the repository is used for the database through use of hibernate and spring data jpa.

-> Security is configured to handle attacks an jwt token auhtenitcation and generation.

-> dtos are used to bridge the front-end api calls to the backend server just so that we don't expose the database to the public.
    

