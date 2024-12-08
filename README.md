# ui-task

Frontend Application for Quote Management
This is a simple frontend application built to interact with APIs for user login, quote management, and image upload. The project is designed with three main pages: Login, Quote List, and Quote Creation. It is responsive and optimized for mobile devices.
--------------------------
Technologies Used
HTML
CSS (Responsive Design)
JavaScript (Fetch API for HTTP requests)
API Endpoints Used
-----------------------------
Login:

POST https://assignment.stage.crafto.app/login
Headers: Content-Type: application/json
Data: { "username": "sandy", "otp": "1234" }
-----------------------------------------

Image Upload:

POST https://crafto.app/crafto/v1.0/media/assignment/upload
Form Data: file=@"/<PATH>/<NAME>.jpg"
----------------------------------------------

Create Quote:

POST https://assignment.stage.crafto.app/postQuote
Headers:
Authorization: <TOKEN>
Content-Type: application/json
Data: { "text": "This is a quote", "mediaUrl": "https://media.crafto.app/home/900x900/4653c87a-83f8-4326-afa0-1a06086550ef?dimension=900x900" }
------------------------------------------------------------------------------------
Get Quotes:

GET https://assignment.stage.crafto.app/getQuotes?limit=20&offset=0
Headers: Authorization: <TOKEN>
--------------------------------------------------------
Installation Instructions
Clone the repository:

bash
Copy code
git clone <repository_url>
Navigate into the project folder:

bash
Copy code
cd <project_folder>
Open the index.html file in a web browser to run the application locally.

The application is designed to be responsive, ensuring an optimal experience on both desktop and mobile devices.
The login and quote creation processes interact with APIs to manage user sessions and quote data.
You can try the app using the username sandy and OTP 1234.







