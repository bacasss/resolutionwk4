INVENTORY tracker API

a simple inventory management API with FastAPI where users can create an API key, manage stock and track low inventory items

FEATURESSSSSSSSS:

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

/docs pageee:
<img width="1919" height="1199" alt="Screenshot 2026-04-16 032925" src="https://github.com/user-attachments/assets/b064455c-5eec-4abf-bc4a-128277453c0b" />



HOW TO RUN:
testpypi link: https://test.pypi.org/project/resolution-week4-bacasss/0.0.1/
1. open command prompt
2. run pip install -i https://test.pypi.org/simple/ resolution-week4-bacasss==0.0.1
3. run uvicorn resolution_week4_bacasss.main:app --reload
4. open http://127.0.0.1:8000/docs and profit :D


ENDPOINTSS:
/register (POST):
Registers you and gives you an API key:
<img width="1182" height="1178" alt="image" src="https://github.com/user-attachments/assets/da774c37-64ae-425c-8ad6-2fd23ab0094b" />


/items (POST):
Requires your API key, then prompts you for details like item name, item quantity, and to define the threshold for when the item is low in stock.
<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/00e9d2a5-39ed-4cac-bb78-5b391321bd25" />


/items (GET):
Shows the list of items in your inventory after you provide your API key.
<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/6f9552da-7589-418b-a845-f630aef74b3f" />

