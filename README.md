# Employee_function
we will create a REST API to add employees to the employee list and get the list of employees.
example
Add Employee:

curl -X POST http://localhost:8080/api/employees \
     -H "Content-Type: application/json" \
     -d '{
           "firstName": "Jane",
           "lastName": "Doe",
           "email": "jane.doe@example.com"
         }'
Get Employees:

curl -X GET http://localhost:8080/api/employees