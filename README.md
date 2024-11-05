# FiveM CAD System

## Overview
The FiveM CAD (Computer-Aided Dispatch) System is a robust web-based application designed for managing law enforcement, emergency services, and dispatch operations within the FiveM gaming platform. This system aims to enhance role-playing experiences by providing structured management of characters, vehicles, weapons, and incidents.

### Key Features

- **User Management:**
  - Create and manage user accounts with roles such as Police Officers, Paramedics, Firefighters, and Dispatchers.
  - Role-based permissions ensure that users can access only the features relevant to their position.

- **Character Management:**
  - Add, edit, and delete character profiles with comprehensive details, including:
    - First Name
    - Last Name
    - Occupation
    - Date of Birth (must be 18+)
    - Gender
    - Address
    - Postal Code
    - City
    - Profile Image Upload

- **Vehicle Management:**
  - Keep track of vehicles associated with each character, allowing for detailed record-keeping of vehicle information.

- **Weapon Management:**
  - Manage records of weapons linked to characters, with options for whitelisting certain weapons for gameplay balance.

- **Arrest Management:**
  - Document and manage arrest reports efficiently, ensuring that all incidents are recorded and accessible.

- **Search Functions:**
  - Quick access tools for searching civilians, vehicles, and warrants, making it easy to find relevant information.

### Database Structure
The application uses a structured MySQL database to store user, character, vehicle, weapon, and arrest data, providing fast access and management capabilities. Key tables include:
- `users`
- `characters`
- `characters_vehicles`
- `characters_weapons`
- `arrests`

### Upcoming Release
This project will be released soon, providing powerful tools for role-playing scenarios in FiveM. The application is actively being developed, and your feedback is invaluable! 

### Contributing
Contributions are welcome! If you have suggestions, improvements, or find any issues, feel free to open an issue or submit a pull request. 
