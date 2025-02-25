# CS360 Mobile App Development Reflection

1. _Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?_
My Warehouse Inventory App was designed to help users track, manage, and update inventory efficiently. It focused on small business owners and warehouse managers who need a simple yet effective way to monitor stock levels and receive low-inventory alerts via notifications and SMS. My primary goals were to:
- Provide a user-friendly inventory management system
- Allow CRUD operations (Create, Read, Update, Delete) for items
- Enable notifications for low-stock items
- Ensure security through login authentication

2. _What screens and features were necessary to support user needs and produce a user-centered UI for the app?_
To meet the user needs, my app included
- Login Screen: Secure access for users.
- Inventory Display Screen: Shows all items in a structured RecyclerView grid.
- Settings Screen: Allows users to set low-stock thresholds for notifications.
- SMS Permission Screen: Ensures transparency when requesting SMS permissions.
 
I wanted my design to have simple, intuitive navigation with clearly labeled buttons. I created a consistent color scheme and UI hierarchy to improve readability. With my user centered design considerations, I also implemented adaptive layouts for different screen sizes.

3. _How did you approach the process of coding your app?_
For my app, through modular developement I separated logic into DatabaseHelper, DataAdapter, and activity classes for better maintainability. I used the RecyclerView with a ViewHolder pattern to handle large inventories smoothly. Integrated SQLite for storing inventory data and SharedPreferences for user settings. I also ensured proper runtime permission requests for sending SMS alerts. I think for future use these strategies can be applied in any scalable mobile app requiring data management, background notifications, or dynamic UI elements.

4. _How did you test to ensure your code was functional?_
I unit tested and checked database operations (inserting, updating, deleting items). By UI testing I ensured smooth RecyclerView scrolling, button clicks, and screen transitions. My implementation of permissions testing verified that SMS alerts only trigger with user consent. I also ran tests on different screen sizes and Android versions. I think all of this is crucial because testing helped me identify UI inconsistencies and performance issues, ensuring a bug-free, reliable user experience before finalization.

5. _Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?_
A big challenge I had was handling low-inventory alerts dynamically without affecting app performance. To solve this I used background checks with SharedPreferences to trigger notifications only when thresholds were met, preventing unnecessary alerts.

6. _In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?_
I think I particularly successfully implemented real-time notifications and SMS alerts, which demonstrated my knowledge of Android notifications, SQLite operations, and permission management. This feature enhanced usability by ensuring users were always informed about stock levels.

 The experience gained from this project will be invaluable for my future mobile development projects!
