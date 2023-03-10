# MusicLibrary

Music Library application keeps track of songs being played by various users in the system. There are three major entities in the system:
1. Songs
2. Users
3. Artists

Each of these entities will have 2 more attributes:
1. Instance level attribute "ID"
2. Static variable named "counter", which will be initialised with 1. In each object creation, the "ID" attribute will be set as the current value of this variable. And after the object creation, this static variable needs to be incremented by 1. 

The system will have have the provision of registering users with the following attributes:
- First name
- Last name
- Contact
  - Email ID
  - Phone
- Address
  - City
  - Locality
  - State
  - Pin Code 

Once the user completes registration, the system should also capture the time(Format: dd/MM/yyyy hh:mm:ss AM/PM), when the user has registered.

We can also add artist with the following attributes:
  - First name
  - Last name
  - List of Songs released

We will capture the following details for songs:
  - Title
  - Genre
  - Release year
  - Language
  - Total Listens

The songs should also record which artist by artist ID.

There should be another class created with the name MusicLibrary, which will keep track of the list of all users, songs and artists. it will also store the user's history of playing songs. This will support the following operations:

- Register a user
- Register an artist
- Release a song
- Mark a user playing a song
- Get top 10 songs for a specific user
- Get top 10 songs overall
- Get the list of songs of a specific artist

Note:

All the operations which take any user input should do proper validation for user,artist and song identifiers. The system should always ensure that it doesn't stop because of the user giving wrong inputs.
