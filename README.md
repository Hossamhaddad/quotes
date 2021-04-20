# quotes

## lab 8 OO Design and GSON
### 1. I created a quote class that make a quote object that contains of author and the quote text 

### 2. randomQuote : A method that use a json file and a reader to read the json file and print a random quote from the quotes saved in the file .

### lab 9 Web requests 

### 1. I created a ApiQuotes Class that make a quote object that contains of author and the quote text

### 2.getJsonFromApi : a method that takes a url as parameter if the url status is 200 (working) this method call another method Called getBufferedReader() if the url is not working or if there is any problem with net connection this method calls the random quote method 

### 3. getBufferedReader : a method that takes the json from the api url 

### 4.  getContent : a method that takes BufferReader file and use a String builder to return the data as string 

### 5. addQuotesToJsonFile : a method that takes the json data and print a random quote and save it inside the json file to be used again using the randomquote Method  

