# QuotesApp

## Cloning the Repository

1. Open Visual Studio Code (VS Code).
2. Open a terminal in VS Code.
3. Clone the repository to your working directory by typing the following command:
   ```bash
   git clone https://github.com/salelkarayush/QuotesApp.git
Setting Up the Backend
Navigate to the backend folder:
bash
Copy code
cd QuotesApp/backend
Create a .env file in the backend folder and add the following content:
makefile
Copy code
DATABASE_KEY = "mongodb+srv://certifiedcoders:wLDQ5WjysaWfUIz0@eventmanager.lxtd08i.mongodb.net/quotes"
Secret_Key = "$$@@CertifiedCoders@@$$"
Save the .env file.
Installing Backend Dependencies
In the terminal, ensure you are in the backend directory and type:
bash
Copy code
npm install
Setting Up the Frontend
Go back to the main directory:
bash
Copy code
cd ..
Or open a new terminal.
Navigate to the frontend folder:
bash
Copy code
cd frontend
Install the frontend dependencies:
bash
Copy code
npm install
Building the Frontend
In the frontend directory, build the frontend:
bash
Copy code
npm run build
Running the Website
Navigate back to the backend folder:
bash
Copy code
cd ../backend
Start the server by typing:
bash
Copy code
npm start
Your website should now be up and running!
