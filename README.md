# Sudoku API
A simple API written in GO used by students in my high school CS class for their Sudoku project. The API includes just one endpoint that can be called to receive uniquely generated Sudoku puzzles. A current version of this API is hosted at https://desolate-shelf-37913.herokuapp.com

### The ```/puzzle``` endpoint
The "puzzle" endpoint can be called using a GET request. The response contains two encoded strings representing the starting state of a Sudoku grid, and the puzzle's solution. Each time a request is made, a unique puzzle is generated. 

Response:
```
{
    "sln": "698754321754321986321986754987645213563219847412873695875462139249137568136598472",
    "start": "....5432175.....8.3........9.....2.3.6.219.4.41..73.9....4.21..2...37.6.13......."
}
```

### Deployment
This app was deployed to Heroku following the guide available [here](https://devcenter.heroku.com/articles/getting-started-with-go#deploy-the-app). 
