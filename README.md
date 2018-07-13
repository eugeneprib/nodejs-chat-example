# Chat Example
User Routes:
  - GET "/api/user?connectedWithId=<id>" - All connected users ever with exact user by id
  - GET "/api/user/<id>" - User by id
  - POST "/api/user/" - Create user with data ({ name: "", email: "" })
  - PUT "/api/user/" - Update user by id ({ id: "", set: { name: "" } })
  - DELETE "/api/user/<id>" - Delete user by id
  
Message Routes:
  - GET "/api/msg/<id>" - Get message by id
  - POST "/api/msg/" - Create message with data ({ senderId: "", receiverId: "", body: "" })
  - PUT "/api/msg/" - Update message by id ({ id: "", body: "" })
  - DELETE "/api/msg/<id>" - Delete message by id
