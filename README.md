The WordPress REST API provides API endpoints for WordPress data types that allow developers to interact with sites remotely by sending and 
receiving JSON (JavaScript Object Notation) objects. JSON is an open standard data format that is lightweight and human-readable, 
and looks like Objects do in JavaScript; hence the name. When you send content to or make a request to the API, 
the response will be returned in JSON. This enables developers to create, read and update WordPress 
content from client-side JavaScript or from external applications, even those written 
in languages beyond PHP.

REST API Developer Endpoint Reference #

Resource 	Base Route

Posts ->	/wp/v2/posts

Post Revisions ->	/wp/v2/revisions

Categories ->	/wp/v2/categories

Tags ->	/wp/v2/tags

Pages ->	/wp/v2/pages

Comments ->	/wp/v2/comments

Taxonomies ->	/wp/v2/taxonomies

Media ->	/wp/v2/media

Users ->	/wp/v2/users

Post Types ->	/wp/v2/types

Post Statuses ->	/wp/v2/statuses

Settings ->	/wp/v2/settings


API END POINT: 
Posts: http://example.com/wp-json/wp/v2/posts/