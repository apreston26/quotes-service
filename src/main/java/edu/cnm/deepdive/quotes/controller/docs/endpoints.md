## REST Endpoints

* `/quotes`

    *  `GET`
    
        * Request: (none)
        * Response: `Quote[]`
    
    * `POST`
    
        * Request: 
            * Body: `Quote`
        * Response: 
            * Body: `Quote`
        
* `/quotes/search`

    * `GET`
    
        * Request: 
            * Query: 
                * `q` : `String`
        * Response:
            * Body: `Quote[]` 
* `/quotes/{id}`

    * `Get`
        * Request 
            * Path: `id` : `long`
        * Response: 
            * Body: `Quote`
            
