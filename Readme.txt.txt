This is a capstone project offered by Coursera "Meta Backend Developer Professional Certificate" course.
The project aims at demonstrating web development skills by writing code to create an API that handles table bookings for the Little Lemon restaurant. The API can receive HTTP requests such as GET, POST, PUT and DELETE, and updates the Django models, which in turn, updates the data in a MySQL database. Reviewers can test the api using below endpoints.

Project endpoints as below:

/auth/users/ 

# to login and auth get token
/api-token-auth/ 
# to login using JDOSER endpoint
/auth/token/login 

# menu items
/restaurant/menu/
/restaurant/menu/{menuItemId}

# table booking 
/restaurant/booking/tables/
/restaurant/booking/tables/{bookingId}