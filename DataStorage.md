Decision: use a server-side database like Realm for data storage in the retail app.

Rationale: The app has to save data locally on the device in order to enable offline mode. The app may store product details, order history, and loyalty program information by using a local database like Realm. User accounts, preferences, and other information that has to be synced when an internet connection is available must also be stored in a server-side database. 

Result: The software can function offline while keeping data synchronized when an internet connection is available due to a server-side database and local device storage working together. As a consequence, the user experience, data accessibility, and the app itself will be improved.



