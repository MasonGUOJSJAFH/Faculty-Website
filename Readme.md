GET all the staff: send a GET request to http://localhost:3000/staff
A faculty of information: send a GET request to http://localhost:3000/staff/1
For a faculty research results: send a GET request to http://localhost:3000/research/1
To obtain a faculty article: send a GET request to http://localhost:3000/articles/1
Update a faculty of information: send a PUT request to http://localhost:3000/staff/1, sets the request body to:
{
"name": "New Name",
"title": "New Title"
}
