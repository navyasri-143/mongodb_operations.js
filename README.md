A program with basic commands on databases and collections using MongoDB
How to Run the Program:
1. Start MongoDB (if not running already):
mongod --dbpath /data/db
2. Run the script:
node mongodb_operations.js
3. Check the inserted data in MongoDB:
mongo
use foodDeliveryDB
db.orders.find().pretty()
