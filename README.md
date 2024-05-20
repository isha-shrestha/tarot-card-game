# tarot-card-game
## This project prompts the user to choose 4 cards and gives their tarot reading.<br/><br/>

 This project has a GUI interface that is built using the Tkinter library.<br/>
 The GUI contains buttons with cards as images.<br/>
 The 22 card buttons correspond to 22 cards of major arcana.<br/>
 The placement(upright or reverse) as well as the sequence of the cards generated are random.<br/>
 The generated sequence as well the chosen cards are stored in a list.<br/>
 The cards' meanings are stored in meaning.py

This program has the following functions:<br/>
+**main()**<br/>This function calls the **GUI()** function
+**tips_title()**<br/>(created for the sake of meeting CS50 criteria)<br/>This function returns the text for the title of tips section.<br/>
+**tips_text()**<br/>(created for the sake of meeting CS50 criteria)<br/>This function returns the text for the body of tips section.<br/>
+**button_click(card)**<br/>This function is called when a button is clicked, i.e, a card is chosen.<br/>This function appends the card clicked(chosen) by the user into a list called **chosen_list**.
+**GUI()**<br/>This function is responsible for all of the front-end and most of the back-end portion of this program.<br/><br/>***For the backend portion***<br/>It generates the random sequence of the tarot card and stores it in a list **cards**<br/>It also stores a list of Tkinter buttons and stores it in a list called **btn**<br/>The sequence and the card number and the position of the chosen cards are used to extract meaning from the list of dictionaries **CardList**<br/>This function also displays the final reading.<br/><br/>***For the frontend portion***<br/>It inserts the title and icon of the GUI window.<br/>It displays the button as per the specified grid on the screen and also adds image to the button


