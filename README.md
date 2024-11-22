# restful-booker-postman
I created this project to test requests of API restful-booker using Postman, Main goal was to improve my experience in testing REST API.

Link to API documentation: https://restful-booker.herokuapp.com/apidoc/index.html

The main collection has name "Booking". It has subcolletions: "Get Booking Tests", "Create Booking Tests", "Update Booking Tests" and "Delete Booking Tests".
"Get Booking Tests" tests GET endpoint /booking 
"Create Booking Tests" tests POST endpoint /booking
"Update Booking Tests" tests PUT endpoint /booking/:id
"Delete Booking Tests" tests DELETE endpoint /booking/:id

I recommend run all subcollection together. Generated collection variables in request "Validate all IDs and create variables" are used by next requests. So first run "Get Booking Tests" subcollection. The last one I recommend run "Delete Booking Tests" subcollection.

# Configuration
Import "Booking.postman_collaction.json" and "Test Environment.postman_environment.json" files to Postman. 
Instruction how to do it: https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-from-git/

# Contact
If you have some question or advice please let me know on email: tarnavsky.piotr@gmail.com
