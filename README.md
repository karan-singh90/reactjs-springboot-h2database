curl --location 'http://localhost:5000/users'

curl --location 'http://localhost:5000/users' \
--header 'Content-Type: application/json' \
--data '{
    "firstName": "AMit",
    "lastName": "Singh",
    "username": "Amit",
    "password":"singh",
    "salary": 1203,
    "age": 12
}'

curl --location 'http://localhost:5000/users/5'

curl --location --request DELETE 'http://localhost:5000/users/5'

curl --location --request PUT 'http://localhost:5000/users/4' \
--header 'Content-Type: application/json' \
--data '{
    "id": 4,
    "firstName": "Ankit",
    "lastName": "Singh",
    "username": "Ankit",
    "salary": 12,
    "age": 23
}'
