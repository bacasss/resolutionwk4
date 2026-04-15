INVENTORY tracker API

a simple inventory management API with FastAPI where users can create an API key, manage stock and track low inventory items

FEATURESSSSSSSSS
API key checking thingamabob
View full inventory
Add items to inventory
Delete items from inventory
Update inventory stock
Filter by items with low stock
Stored by a database (NOT JSON)
Rate limited
Background logging of inventory changes/actions

run inventory (i think) orrrr uvicorn main:app --reload (more reliable)
then open http://127.0.0.1:8000/docs