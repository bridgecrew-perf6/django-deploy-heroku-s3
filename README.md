# django-deploy-heroku-s3

- This is an REST api created using Django Rest framework and hosted on Heroku. S3 buckets on AWS are also used for database transfer.
- Hosted on: https://fyle-test-dev.herokuapp.com/
- Use the following type of commands to retrieve data:

  - Autocomplete API to return possible matches based on the branch name ordered by IFSC code (ascending order) with limit and offset.
    - Endpoint: /api/branches/autocomplete?q=<>
    - Example: /api/branches/autocomplete?q=RTGS&limit=3&offset=0
      
  -  Search API to return possible matches across all columns and all rows, ordered by IFSC code (ascending order) with limit and offset.
  - 
    - Endpoint: /api/branches?q=<>
    - Example: /api/branches?q=**Bangalore**&limit=4&offset=0
 
 - Do mention offset and limit to make valid rest apis
