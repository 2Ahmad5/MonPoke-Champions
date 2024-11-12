# MonPoke Champions

# Milestone 4 Demo Link: https://duke.box.com/s/zz702p8o736i7ts0aukh89xnqg13ot7g
# Prototype Code Repo: https://gitlab.oit.duke.edu/ndp25/cs-316-proj
# Main Repo: https://github.com/2Ahmad5/MonPoke-Champions

## 🏆 Project Category: Open Project

### 👥 Team Members:
- **Ahbab**
- **Ahmad**
- **Nolan**
- **Richard**
- **Seung Hyun**

---

## 🛠 What We've Accomplished since Milestone 3:

### Role Clarification:
Each team member has clearly defined their roles, ensuring smooth collaboration and focused efforts.

### Development:
- **Richard** has implemented:
  - Begun the implementation of the game itself and has the skeleton of the game implemented
  - implemented the hosting of games to play multiplayer matches
  - During a turn, players can use minion or spell cards
  - during turns players can place cards and do damage to the opposing players and can win a game
  - When a player has lost all their health the game ends
  - Connected to the database with API calls to login and get User inventories
 
- **Ahbab** has implemented:
  - A new user can register for a new account; an existing user can log in using username and password.
  - Each user account has a system-assigned id. Other account information includes email, full name of user, and password.
  - Users can update all information except the id. Ensure that username is unique among all users.
  - Each account is associated with a MonPoke currency. It starts out as $0, but can be topped up by the user (either through playing the game or buying it using real money). 
  - Provide a way for user to view their profile. It will show the account number, MonPoke currency, name as well as collected MonPoke and match history. 
  - Implement a way for users to view OTHER people’s profile through a search functionality. Users can seach based on other users’ username.
  - Wrote API calls so that the unity game can send Post and Get reqeusts to the database
 
- **Ahmad** has implemented:
  - Users can go on a separate tab to view a MonDex where all the MonPoke’s are listed to view relevant information. Options will exist on the tab to filter to make it easier to view MonPokes. Example would be only wanting to view fire types, etc.
  - All the MonPokes will be listed as types of species and within a Users data, the MonPokes they have will be stored.  
A variety of MonPoke will reside in this database
  - A separate table just storing all the different characters, their types, attacks, and other similar attributes.
  - A monDex page on the websate displaying the image, type, health, damage, rarity, strengths, and weaknesses of the cards

- **Nolan** has implemented:
  - Each user has access to the Microtransaction Store. Items in the store will be packs that give the user a random card, drawn from the database of cards, with higher rarity cards being less likely to be drawn. Different packs will be able to give different types of cards. Each item in the store will have a designated price. All items in the store will be available to the user.
  - Users can use an in-game currency to buy one or multiple items provided they have the balance. After completing an order, their balance will be decreased and they will open the pack and the cards will be added to their inventories.
  - Users' purchase history will be tracked and can be viewed in the store interface and will include the date of purchase and purchase cost.
  - Users can have a cart that will allow them to mass purchase different items. The cart will remain through log-outs.
  - Can add currency with a basic form submission at the moment
  - Users can use “real” money to buy additional currency. It will require the user to add their payment info and then the in-game currency can be added to their balance. For the purpose of the project, we will not deal with real credit cards
  - When a user purchases a card, the card they drew pops up with the color of the rarity.

- **Seung Hyun** has implemented:
  - Provide a way for user to view their profile. It will show the account number, MonPoke currency, name as well as collected MonPoke and match history. 
  - Implement a way for users to view OTHER people’s profile through a search functionality. Users can seach based on other users’ username.
  - Implemented a leaderboard that sorts by the users number of wins


### Repository Setup:
We’ve successfully created this GitHub repository to manage our project’s codebase and collaborate efficiently.

### Team Name Finalized:
We proudly settled on the team name **MonPoke Champions** to represent our project moving forward.



### What we plan to do next:
- Finish implementing some of the advanced features that we have not completed
- Implement the ability for players to leave feedback through forums and forms
- Add style and make the website look nice
