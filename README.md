
## Description 

- 1. Create a full stack app using React, MongoDB, and Nodejs.

- 2. Create an admin login and a user login with complete registration, authorization, email verification.

- 3. After logging in, users should be able to view the available pizza varieties in the dashboard.

- 4. Integrate the payment gateway for checkout for payment. Create a dummy account and integrate the test mode. In testmode, on clicking success, place and confirm the order.

- 5. Admin must receive the order and change the status of the pizza- as order received, In the kitchen, and Sent to delivery.

- 6. For every update from the admin, the status change must be reflected in the user dashboard.

## Tech-stack
- node.js
- express.js
- socket.io
- payment integration (stripe api)

## Demo 


https://github.com/vedantraval2310/OIBSIP_Level3_pizza_delievery_application/assets/76436755/24374299-92c0-4156-b0b0-74160eabec96


https://github.com/vedantraval2310/OIBSIP_Level3_pizza_delievery_application/assets/76436755/b1074a81-a4c1-4475-841b-33191bad94fc



## Installation 

- After download or clone run `npm install` to install all the dependancies.

- Then after open test account in payment gateway (Razorpay) and paste secret key in .env file and publishable key in resources file. 

- Then after create a database named 'pizza' in MongoDB and create a collection named menus and paste 'menus.json' to collection. 

- So now our project is ready to run. To run project run 'node server.js' command in terminal.

🙏 If you find this repo helpful then don't forget to give a star ❇️ to this repository. :)
