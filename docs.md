**Show State data**
----
  Returns json data about a state corona cases.

* **URL**

  /api/getData/:state

* **Method:**

  `GET`
  
*  **URL Params**

   **Example:**
 
   `/api/getData/assam`


* **Success Response:**

    **Content:** `{"status":200,"state":"assam","current_data":{"confirmed":90,"recovered":41,"deaths":45,"total":176}}`
 
* **Error Response:**
  If you entered a state that is not in dataset
    **Content:** `{"status":200 , error : "No such state found" }`


