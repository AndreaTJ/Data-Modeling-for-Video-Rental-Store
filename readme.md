# *Project: VideoClub Management System*

## *Overview*:

During a family meal, your cousin mentions that he has recently opened a video rental store, but it's not doing as well as he had hoped. He believes the issue lies in the lack of proper software to manage loan records and the inventory of movies. Despite suggesting the competition from services like Netflix as a potential cause, you see his enthusiasm and decide to lend a hand.

### Functional Requirements:

After digesting a hearty meal, your cousin details the following requirements:

- **Member Registration**: The system needs to register members of the video rental store. Required information includes their name, surname, date of birth, phone number, and identification number (DNI, Passport, or equivalent in your country). A unique member number will be assigned by the system for issuing membership cards, reflecting a charmingly retro approach reminiscent of the 1990s.

- **Address Registration (Optional)**: Members' mailing addresses need to be registered for potential advertising campaigns. However, it's not mandatory for a member to provide this information. Details such as postal code, street name, number, and apartment are sufficient, assuming they are located in the same city as the video rental store.

- **Movie Registration**: The system must manage movie records. It's possible to have multiple copies of the same movie. Essential details include the movie's title, genre, director, and synopsis.

- **Loan Records**: It's crucial to track which member has borrowed each copy of a movie, including the date of loan and return. A movie is considered loaned out if it lacks a return date.

- **Query Availability**: The system should enable frequent queries to determine which movies are currently available for rental (i.e., not loaned out), including the title of the movie and the number of available copies.

### Delivery:

This project will be delivered in two parts:

1. Entity-Relationship Diagram: An ER diagram in draw.io format, outlining the relationships between members, movies, and loans.

![DiagramaEntidad](./videoclub.drawio.png)

2.  SQL Script: This script will create a new schema, establish all necessary tables, populate them with data, and include two queries (though only the last one will be displayed, both are required). This part focuses on the practical implementation of the database structure and data manipulation.


[Script SQL](./videoclub.sql)

**[Extracted text from a practice exercise by Keepcoding - Glovo Data Analysis Scholarship, 2024]**
