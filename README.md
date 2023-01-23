# telescope-booking
Webpages for telescope slot booking and creation for Cepheid.

### Tech Stack
- Frontend: React
- Backend: Node
- Database: MYSQL
- Misc: Express, Axios, Sequelize

### Installation
To install dependencies, run\
npm install

Edit URL in frontend/src/components/TelescopeBooking.js to be the address of the backend server.

Create a database 'cepheid' and two tables. Use the commented code in backend/index.js \
Manually insert email ids of admins into the table admin

backend/serviceAccount.json is not public here

## Features

### User
- Book a slot
- User and guide details are hidden from other users

### Admin
- Create a slot
- Cancel a slot
- Clear past slots from database
- Sees all details for slots

### Colour code
- Blue: available
- Red: not available
- Green: booked
