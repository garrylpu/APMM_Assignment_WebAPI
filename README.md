# APMM_Assignment_WebAPI
This assessment is to build an ASP.NET Core web API for an internal dashboard application to track container transport prices for specific geographical routes, referred to as voyages. More specifically, your API needs an endpoint that returns the last 10 prices for containers booked on a given voyage and an endpoint through which you can register a new booking price. The application should support at least 3 different currencies of your choice. You don't need to connect to an online service to get the latest currency rates - it is fine to use hard-coded exchange rates


Steps to run the build is:
1. Run the VS code.Check with executed URL:http://localhost:49345/api/values
2. Verify if API with an endpoint returns the last 10 prices for containers booked on a given voyage. Voyage Names are e.g.Voyage1,Voyage2 .......Voyage12 along with container_Price, currency and current timestamp.
3. Verify if application supports at least 3 different currencies of 3 choice. e.g USD, EUR,INR. 
4. Open the same executed URL:http://localhost:49345/api/values in new tab and try to fetch 1 record by Voyage id
5. Verify if we get the record by ID giving particular code and currency and receives the Container_Price URL as http://localhost:49345/api/values/Voyage1/USD
6. Open the postman tool to check Get, Get by ID, Put and Post result.
7. Give the executed URL to postman for Get request and verify if API with an endpoint returns the last 10 prices for containers booked on a given voyage. Voyage Names are e.g.Voyage1,Voyage2 .......Voyage12 along with container_Price, currency and current timestamp.
8. Give the executed URL to postman for Get by ID request and verify if API, giving particular code and currency and receives the Container_Price URL.
9. Give the executed URL to postman for Post query and check if new Voyage entry has been added. Also check if all currency is in INR with correct calculation whether inputgiven is in EUR or USD. 
10. 9. Give the executed URL to postman for Put query and check if existing Voyage entry has been modified.
