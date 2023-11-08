# Chat Application
<html>
<body>
<div class="overview"> 
  <p>Here is an overview of my Software Engineering group final project with descriptions, diagrams, and in-app examples explaining each aspect of how this application
      works. The purpose of this project was to create an employee based chatting system so that employees may chat with one another. There are also admin accounts
      with access to more features as well. This application was built mainly in JAVA using Eclipse IDE.</p>
</div>

<div class="architecture"> 
  <h2>Application Architecture</h2>
  <p>Below are visual diagrams showcasing how the main features of the application were designed and how they work in relation to one another. The simplified UML diagram 
    illustrates the entire functionality of the app. The other two diagrams express how each employee's information is stored within the EmployeeList and how each 
    chat log is saved within the system.</p>
  <img id="simplifiedUML" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/6067e3a7-cdb1-4008-856e-767d100a18bf" height="380" width="310" />
  <img id="userDiagram" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/0fe605f4-f373-46e0-9ddf-054514ae892e" height="380" width="300" />
  <img id="chatDiagram" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/d3d0aa8a-9aa1-496e-94ac-491cb18df25a" height="380" width="330"/>
</div>

<div class="login"> 
  <h2>Login and Server Connections</h2>
  <p>Upon opening the app, a user is greeted with a Login page as per any usual application, and would use their employee credentials that were created by an Admin.
    During development, we created a simple virtual server design that allows multiple users to be able to connect to the systems at any given time. This also 
    allowed us to track when a user is online for new chat conversations.</p>
  <img id="login" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/ebd66d0e-de44-4a2a-882f-a9e9f28425fd" height="400" width="" />
  <img id="userConnections" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/cb3daca0-d82e-465c-ba9e-4c6cad279d0b" height="400" width=""/>
</div>

<div class="chat"> 
  <h2>Chat Features</h2>
  <p>We developed basic chat functionality which allowed for 1-on-1 conversations, along with group chats as well. A user is able to create a chat with another user or users,
    regardless of online status. Once the offline user logs in, they will retrieve notifications of all messages missed. Each conversation is then stored for future 
    access.</p>
  <img id="chat" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/07566dbb-0888-4b67-9573-3338baf7a629" height="330" width=""/>
  <img id="groupChat" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/50224f1b-e19a-4bdb-aacc-dc50e503a020" height="330" width=""/>
</div>

<div class="settings"> 
  <h2>Admin Settings </h2>
  <p>Special Admin accounts are also a employee accounts but with access to hidden features within the settings tab. An admin is able to create new users (employee or admin), 
    delete users (only employee), and view all exisiting chats that do not contain an Admin within them. They are not able to edit or delete previous chat conversations. </p>
  <img id="settings" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/4fffaef1-6b94-4bec-abab-9b5575da764f" height="370" width=""/>
  <img id="createUser" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/fb636fb0-a024-409c-bc6a-fe3e9715982a" height="370" width=""/>
  <img id="adminAccessUsers" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/0a75b74b-2c2c-46ca-85fc-922822a6e7d8" height="330" width=""/>
  <img id="adminAccessChats" src="https://github.com/Manny820/Software-Engineering-Final/assets/98365823/c45ddaa7-1738-4b4c-8f5e-21f2ad4a0259" height="330" width=""/>
</div>

</body>
</html>
