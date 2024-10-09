<h1>Flashcard Fullstack Web app</h1>

<p align="center">
  
![alt text](https://github.com/justusa212/flashDemo/blob/main/app%20screenshot%202.png)

![alt text](https://github.com/justusa212/flashDemo/blob/main/app%20screenshot.png)

</p>


**Get Decks**
----
 Get all decks
* **URL**

  /decks/

* **Method:**

  `GET`
  
*  **URL Params**
 
* **Body Params**

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

 **Create Deck**
----
 Create a deck
* **URL**

  /decks/

* **Method:**

  `POST`
  
*  **Body Params**
    Title
 
* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

 **Delete Deck**
----
 Deletes a deck
* **URL**

  /decks/:deckId

* **Method:**

  `DELETE`
  
*  **URL Params**
    deckId

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

 **Get Deck**
----
 Gets a specific deck
* **URL**

  /decks/:deckId

* **Method:**

  `GET`
  
*  **URL Params**
    deckId

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

**Make card inside Deck**
----
 Make a card inside a deck
* **URL**

  /decks/:deckId/cards

* **Method:**

  `POST`
  
*  **URL Params**
    deckId

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

**Delete card inside Deck**
----
 Deletes a card inside a deck
* **URL**

  /decks/:deckId/cards/:index

* **Method:**

  `DELETE`
  
*  **URL Params**
    deckId, index

* **Success Response:**

  * **Code:** 200 <br />
    **Content:** `{title: string, cards: string array}`

