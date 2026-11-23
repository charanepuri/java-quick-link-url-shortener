# Quick Link – URL Shortener
 
## Project Description
A command-line adaptation of the Quick Link URL Shortener concept. Users submit a long URL, receive a generated short code, and can look up the original URL using that code. The console edition demonstrates the mapping logic locally.
 
## Technology Stack
Java (JDK), OOP, Scanner, HashMap, URI/URL validation, Random or SecureRandom, file handling, and exception handling.
 
## Features
- Accept a URL from the console and validate its format.
- Generate a compact unique short code.
- Store a mapping between each short code and its original URL.
- Retrieve and display the original URL using a short code.
- Prevent or retry short-code collisions.
- List saved URL mappings.
- Optionally persist mappings in a local file.
 
## Database Design
No database is required for the basic version; HashMap can hold URL mappings in memory and a local file can provide persistence. An optional relational schema could use UrlMapping(mapping_id, short_code, original_url, created_at), with short_code constrained to be unique. Public redirects need a deployed HTTP server and a reachable domain.
 
## Learning Outcomes
- Use HashMap for key-value storage and lookup.
- Validate and process URI/URL input.
- Generate unique identifiers and handle collisions.
- Persist records using file I/O.
- Understand the difference between local short-code lookup and public HTTP redirection.
 
## Explanation
The user enters a long URL. The application validates the input, generates a short code, checks that the code is unique, and stores the relationship between the code and the original URL. Later, the user can enter the short code to retrieve the original URL. Since this is a console application, it does not automatically create a public redirecting website.
 
## Conclusion
Quick Link introduces key-value data structures, URL validation, identifier generation, collision handling, and persistence. It models the core shortening workflow while clearly separating console functionality from the infrastructure needed for a public URL-shortening service.
 
## Author
**Charan Teja EPURI**  
*Aspiring Full Stack Developer*
 
- [Django Portfolio](https://portfolio-site-django.onrender.com)
- [GitHub](https://github.com/charanepuri)
- [React Portfolio](https://charan-react-portfolio.vercel.app)
- [LinkedIn](https://www.linkedin.com/in/charan-teja-972aa9231)
- [Flask Portfolio](https://flask-developer-dashboard-portfolio.onrender.com/)
