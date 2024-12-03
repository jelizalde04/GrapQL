GraphQL Example: Querying Countries
This is a simple example of how to use GraphQL to query information from a public GraphQL API. In this case, we're querying a list of countries and retrieving their names and codes.

How to Use
Clone or Download the Project

You can either clone the repository or download the HTML file directly to your computer.
Open the HTML File

Open the index.html file in your preferred web browser (e.g., Chrome, Firefox, Safari).
Make a Query

You will see a form with a textarea that contains a default GraphQL query. The query retrieves a list of countries with their name and code.
You can modify the query if you'd like (though the default query should work perfectly).
Submit the Query

Click the "Consult Countries" button. This will send a GraphQL request to the public GraphQL API.
View the Response

The response will be shown below the button in a formatted JSON structure. It will include the country names and their respective codes.
How It Works
GraphQL Query: The query that is being sent is:
{
  countries {
    name
    code
  }
}
This query asks the API to return a list of countries (countries) with their name and code.

Public GraphQL API: The data comes from a public GraphQL API:
https://countries.trevorblades.com/graphql

Response: The API returns a JSON object with a list of countries, which is then displayed on the web page.

Example Response
After submitting the query, the response will look something like this:
{
  "data": {
    "countries": [
      {
        "name": "Afghanistan",
        "code": "AF"
      },
      {
        "name": "Albania",
        "code": "AL"
      },
      {
        "name": "Algeria",
        "code": "DZ"
      },
      {
        "name": "Andorra",
        "code": "AD"
      },
      {
        "name": "Angola",
        "code": "AO"
      }
    ]
  }
}
Sure! Here’s a simple README in English explaining how to use the GraphQL example:

GraphQL Example: Querying Countries
This is a simple example of how to use GraphQL to query information from a public GraphQL API. In this case, we're querying a list of countries and retrieving their names and codes.

How to Use
Clone or Download the Project

You can either clone the repository or download the HTML file directly to your computer.
Open the HTML File

Open the index.html file in your preferred web browser (e.g., Chrome, Firefox, Safari).
Make a Query

You will see a form with a textarea that contains a default GraphQL query. The query retrieves a list of countries with their name and code.
You can modify the query if you'd like (though the default query should work perfectly).
Submit the Query

Click the "Consult Countries" button. This will send a GraphQL request to the public GraphQL API.
View the Response

The response will be shown below the button in a formatted JSON structure. It will include the country names and their respective codes.
How It Works
GraphQL Query: The query that is being sent is:

graphql
Copiar código
{
  countries {
    name
    code
  }
}
This query asks the API to return a list of countries (countries) with their name and code.

Public GraphQL API: The data comes from a public GraphQL API:
https://countries.trevorblades.com/graphql

Response: The API returns a JSON object with a list of countries, which is then displayed on the web page.

Example Response
After submitting the query, the response will look something like this:

json
Copiar código
{
  "data": {
    "countries": [
      {
        "name": "Afghanistan",
        "code": "AF"
      },
      {
        "name": "Albania",
        "code": "AL"
      },
      {
        "name": "Algeria",
        "code": "DZ"
      },
      {
        "name": "Andorra",
        "code": "AD"
      },
      {
        "name": "Angola",
        "code": "AO"
      }
    ]
  }
}
Requirements
A modern web browser (Chrome, Firefox, Safari, etc.).
No server setup is required. This works entirely in the browser.
Troubleshooting
If the query isn't working, ensure that you are connected to the internet as the API is remote.
If the response isn't showing up, try refreshing the page.
