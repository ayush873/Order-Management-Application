# Order-Management-Application
It is a Backend order management application can be used by any company, designed using Node.Js using main dependency as Express,js and MongoDb.
Structure of this application has 4 roles-
  1. Admin/Manager
  2. Dealers
  3. Shopkeepers
  4. Representatives
  

Responsibilities of each role-
    
    1. Admin-
      a. It can add dealers, shopkeepers with shops, representatives.
      b. It can add products.
      c. it have all the access to all the data of the organization.
      
    2. Dealers-
      a. Able to perform bulk ordering towards the company and track status.
      b. Only admin and dealers could view and modify the status.
      c. Able to track orders of the shopkeepers.
      
    3. Shopkeepers-
      a. Able to order products towards dealers and can track them.
      b. his orders can be tacked by dealers, shopkeepers and representatives.
      c. they can track their orders and orders ordered for them by shopkeeprs.
      
    4. Representative-
      a. able to add shopkeepers along with the shops.
      b. able to add his daily visit details.
      c. able to order products for a shop after daily visit.
      d. Once order placed it has to be confirmed by the shopkeeper.
      e. Representative orders can be tracked by Manger/Admin.
      
 A role based authentication system is there, so if a new role(chief manager) is added to organizaton, we will not need to change the architecture.
 Passwords are encrypted using JWT tokens.
 Dependencies can be viewd in package.json file.
 
      
