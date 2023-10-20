# GameSim API Testing
 Small Repo for testing GameSim API and providing feedback. 

### Note that many of the following examples have been run in [Postman](https://www.postman.com), [Boomi](https://boomi.com/)[^1], and Python.


[^1]: Small note on Boomi requests - the default value in Boomi for the 'Accept' header does not include 'text/plain' - at least for the /ping endpoint 'Accept' must be set to include 'text/plain' (or '\*/\*')


## Current Bugs [Notebook With Examples](Bugs-and-Feature-Request.ipynb):
1.  Setting "includeStats" to False in a Simulate request throws a 500 Internal Server Error. 

## Current Requested Features [Notebook With Examples](Bugs-and-Feature-Request.ipynb):
1. Some way to view the remaining calls in the current billing timeframe. 
2. Access to the "Home Field Advantage" and "Show Play-by-Play" fields from the website.
3. Ability to make a predictions call based on the week of play (for CFB and NFL) instead of date.
