

## Uses case

 ### Use case 1: The user registers to the application with an institutional email   
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-01**           |   The user registers to the application with an institutional email                     |
| **Version**           |      1.2 (25/11/2023)                  |
| **Dependencies**           |      User management                  |
| **Precondition**           |      The user has an institutional email                |
| **Description**           |    The user creates a user in the application with their institutional email                     |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | The user enters the application |
|| 2 | The user chooses the registration option |
|| 3 | The user enters an institutional email  |
|| 4 | The user chooses the registration option |
|| 5 | A confirmation email is sent to the email entered |
|| 6 | Email is confirmed |
||7 | The user enters their descriptive data |
|        **Postcondition**    |   The user exists and is current                      | 

 ### Use case 2: The user registers to the application with a personal email  
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-02**           |   The user registers to the application with a personal email                     |
| **Version**           |      1.2 (25/11/2023)                     |
| **Dependencies**           |        User management                    |
| **Precondition**           |      The user has an institutional email                |
| **Description**           |          The user creates a user in the application with their personal email               |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | The user enters the application |
|| 2 | The user chooses the registration option |
|| 3 | The user enters an personal email  |
|| 4 | The user chooses the registration option |
|| 5 | A confirmation email is sent to the email entered |
|| 6 | Email is confirmed |
||7 | The user enters their descriptive data |
|        **Postcondition**    |   The user exists and is current                       | 

 ### Use case 3: The user comments on a post  
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-03**           |   The user comments on a post                   |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Interaction, product publication                 |
| **Precondition**           |      The registered user views the sellers publications.                |
| **Description**           |    The user types a series of characters in the post; the comment is uploaded and the process ends.                   |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | The user views a post |
|| 2 | The user enters the comment box |
|| 3 | The user writes a comment  |
|| 4 | The user presses send |
|        **Postcondition**    |   The post has a new comment                     | 

 ### Use case 4: The user reacts to a post
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-04**           |   The user reacts to a post                   |
| **Version**           |      1.0 (30/10/2023)                  |
| **Dependencies**           |      Interaction, product publication                  |
| **Precondition**           |      The user has a current account in the application.                |
| **Description**           |    The user is interested in a publication and leaves a reaction                     |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | The user views a post |
|| 2 | User accesses the reactions interface |
|| 3 | The user selects a reaction  |
|        **Postcondition**    |   The publication has a new reaction                     | 

 ### Use case 5: The user reports content
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-05**           |   The user reports content                   |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Interaction, product publication                 |
| **Precondition**           |      The user has a current account in the application                |
| **Description**           |    The user notices a post or comment with suspicious or prohibited content                     |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | The user views content (post, comment) |
|| 2 | The user presses the report button |
|| 3 | The system sends the report  |
|        **Postcondition**    |   The publication has a new report                     | 

 ### Use case 6: User rates another user
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-06**           |   User rates another user                  |
| **Version**           |      1.0 (25/11/2023)                  |
| **Dependencies**           |      Interaction, user management                |
| **Precondition**           |     Users have a current account               |
| **Description**           |    A user enters another user's profile to be able to rate their experience dealing with the other user.                     |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The user enters another user's profile |
|| 2 | User selects from 1 to 5 stars |
|| 3 | The user leaves a short review of the other user  |
|        **Postcondition**    |   The user receives a new rating                    | 

 ### Use case 7: 2 users establish a conversation via messaging
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-07**           |   2 users establish a conversation via messaging                |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Comunication, User management                |
| **Precondition**           |     One user plays the role of seller and the other plays the role of buyer.              |
| **Description**           |    A buyer user was interested in a product and wants to contact the seller through the application's messaging                    |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The buyer enters the messaging interface |
|| 2 | The buyer sends a message to the seller |
|| 3 | The seller receives the message notification  |
|| 4 |The seller enters the chat |
|| 5 | The seller answers the message |
|| 6 | The buyer receives the response notification   |
|        **Postcondition**    |   A new chat is created between users                  | 

 ### Use case 8: User lock
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-08**           |  User lock               |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Comunication, User management                |
| **Precondition**           |    Prior communication was established with the user             |
| **Description**           |   A user wants to block another user                   |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The user enters the chat of the user to block |
|| 2 | The user presses the “block” option |
|        **Postcondition**    |  The user is blocked                 | 

 ### Use case 9: User Unlock
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-09**           |  User unlock             |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Comunication, User management                |
| **Precondition**           |    The user had previously blocked another user             |
| **Description**           |   A user wants to lift the block set on another user                  |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The user enters the chat of the user to be unblocked |
|| 2 | The user presses the “unblock” option |
|        **Postcondition**    |  The user is unblocked                 | 

 ### Use case 10: Delete a chat
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-10**           |  Delete a chat             |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Comunication, User management                |
| **Precondition**           |    2 users established a previous conversation             |
| **Description**           |  A user wants to delete the message history generated with another user                 |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The user enters the chat of the user to delete |
|| 2 | The user presses the “Delete chat” option |
|        **Postcondition**    |  The chat is deleted                | 

 ### Use case 11: Product publication
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-11**           |  Product publication          |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      Product publishing, user management               |
| **Precondition**           |   The user has a registered account with an institutional email            |
| **Description**           |  A user wants to advertise the product he sells                 |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 | User accesses publishing interface  |
|| 2 | The user decides how many visual resources to upload (text, photo and/or video)  |
|| 3 |The user adds a description to the product  |
|| 4 |The user sends the publication  |
|        **Postcondition**    |  The publication is uploaded to the platform             | 

 ### Use case 12: Edit profile
|                     |                         |                         |
| ------------------- | ----------------------- | ----------------------- |
| **CU-12**           |  Edit profile          |
| **Version**           |      1.1 (25/11/2023)                  |
| **Dependencies**           |      User management, user presentation             |
| **Precondition**           |   The user has a current account           |
| **Description**           |  The user enters their profile settings to update and personalize it with their data                 |
| **Main flow**           |  **Step**                       | **Action** |
|| 1 |The user enters his profile  |
|| 2 | The user selects the “Edit profile” option  |
|| 3 |The user adds the information of their preference  |
|        **Postcondition**    |  Profile information changes             | 
