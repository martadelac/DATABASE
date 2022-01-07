### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

Is a free and open-source relational database management system that emphasizes extensibility and SQL compliance.

- What is the difference between SQL and PostgreSQL?
PostgreSQL is an extended version of SQL and is open source, while SQL Server is owned and licensed by Microsoft. SQL is the language used to store and query data and PostgreSQL uses that language.

- In `psql`, how do you connect to a database?
Type \c + database name

- What is the difference between `HAVING` and `WHERE`?
  WHERE selects input rows before they are grouped whereas HAVING selects/filter groups.
HAVING is applied to groups of data and WHERE applies to individual rows.


- What is the difference between an `INNER` and `OUTER` join? Most significant difference is that ‘INNER’ joins result in the intersection of two tables, while ‘OUTER’ joins result in the union of two tables

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
OUTER joins can be LEFT, RIGHT, or FULL.

LEFT means data can be in the left table but not in the right and it will show up. RIGHT means data can be in the right table but not in the left and it will show up. FULL join allow all data to be shown no matter if it shows up in both tables or not.


- What is an ORM? What do they do?

ORM stands for “object-relational mapping” and they allows us to convert data between different systems in an object-oriented way. For example, SQLAlchemy can convert data in SQL into objects to be used in Python.


- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
Server requests might help keeping private keys secret since they won't be in the client browser with AJAX.
AJAX requests are asynchronous, and the server is synchronous. AJAX requests must respect the single origin policy (which prevents you from making requests to pages on different domains, different subdomains, or different protocols whereas server requests don't.

- What is CSRF? What is the purpose of the CSRF token?

CSRF stands for cross-site request forgery and it makes possible proving that I am who I say that I am and allows the request to be made depending if I had a token with the rights to do something or not. 
 

- What is the purpose of `form.hidden_tag()`?

It is commonly used to allow values like the CSRF token to be passed through a hidden field on WTForms. This will render all of the hidden input tags.
