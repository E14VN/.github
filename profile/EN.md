# E14VN

### [VI](https://github.com/E14VN/.github/blob/main/profile/README.md) | EN

Project for developing a global emergency alarm (fire, ambulance, police, rescue,...)

## Progress
### Platform
- **Features idea**: Completed | 15/09 - 27/09
- **Research & testing**: Working | 01/10 - Now
- **Project implementation**: Working | 02/10 - Now
    - **Server**: Working | 02/10 - Now
        - Completed system design.
        - Completed registration function.
    - **Mobile application**: Working | 02/10 - Now
        - Completed system design.
        - Completed registration function.
        - Completed notification function.
        - Completed zone selection function.
    - **Software**: Planned | Now
- **Documentation**: Working | 02/10 - Now
- **Test run & hotfixes**: Planned | Now

### Embedded
- **Features idea**: Completed | 15/09 - 27/09
- **Research & testing**: Planned | Now
- **Project implementation**: Planned | Now

## Main features
**1. Speed**:

- Horizontal scaling server: Increase information processing speed by adding Nodes and Balancers.
- Low requirement frontend: A smartphone is enough to use the application.

**2. Convenient**:

- The application operates clearly, easy to use, does not cause confusion, and can be used on smartphone with a network connection.
- The server system is easy to maintain, with documentation available for faster reading and understanding.

**3. Privacy**:

- Do not save any user data to the server unnecessarily. (*)
- All position calculations are performed right on the client side.

*Location storage is only performed on a user when that person reports an emergency.

**4. Free for everyone**:

Non-profit product with the purpose of bringing safety to everyone. Donations can be made to the project.

Costs incurred when using the project in the distribution plan:

**Option 1 (being integrated):**
- **Server infrastructure: Run E14's servers so the platform can operate.**
    - [MongoDB](https://www.mongodb.com) (If using third-party hosting service): Stores registered user information and station locations.
    - [Twilio](https://www.twilio.com/): Phone number verification.
    - [Firebase](https://firebase.google.com/): Send notification (No fee).
    - [Google maps API](https://mapsplatform.google.com): Select a location on map.
- **Apps and software: No fees.**

**Option 2 (not integrated):**
- **Server infrastructure: Run E14's servers so the platform can operate.**
    - [Firebase](https://firebase.google.com/): Stores registered user information, locations of stations, sends notifications.
    - [Google maps API](https://mapsplatform.google.com/): Select a location on map.
- **Apps and software: No fees.**

Although it is an open source product, there are some limitations on its intended use.

Xem thêm: [E14 Open Source License](https://github.com/E14VN/.github/blob/main/LICENSE.md)

Summary: Allows the use for learning, understanding and improving the platform. Do not allow the use of the project or too many ideas from it to make a profit.

### Project ideas are established on 15/09/2023 21h37
