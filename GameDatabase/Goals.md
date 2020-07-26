# Goals of the Game Database

This application is to create a public web API to interface with a database that contains information about Games, Developers, Publishers, and Platforms. This database will create relations ships between these Entities so that users can query specific entities through their id or title or search generically for entities based upon their relationships, such as searching for all games based upon their developer or searching all games based upon a title substring.

Also, any changes that are proposed will be held in a queue that allow Moderators and Administrators to approve or disapprove changes to provide a level of quality control in the database.

The api will be secured through using SSL to encrypt the traffic between the client and this server, we will authenticate to the server using OATH bearer tokens that define the following roles:

- User
- Authenticated User
- Moderator
- Administrator

Users will be able to read and search for game data. Authenticated users will also be able to submit changes to Entities for approval. Moderators will be Authenticated Users that can accept or reject submitted changes. Administrators will be able to make direct changes to the database.
