# Ambulance Alert Spec

### **Overview**

One of the biggest obstacles women in the developing world face while pregnant is getting to a health facility to safely deliver. Organizations train motorcycle ambulance drivers to improve this problem, but mothers have a hard time contacting them in time. This app identifies and sends a text to the nearest motorcycle ambulance driver.  

---

### **Technology Stack**

- **Frontend:** React Native
- **Middleware:** Express.js
- **Database:** PostgreSQL

---

### **Features**

**User Registration (Both Driver and Patient Facing)**

- Users should be able to register as either an ambulance driver or someone seeking help. In the registration process, the app should collect data on whether or not someone is an driver, the user's name, the user's phone number.

**Request Help (Patient Facing)**

- Users should be able to easily request transportation from the nearest driver. If the nearest driver is busy, then the request should go to the next nearest driver. If a driver does not accept the request within two minutes, a request should be sent to the next nearest driver.

**Accept Help (Driver Facing)**

- Once a driver accepts a request, Google / Apple Maps should open with navigation to the person seeking help. The user who requested help should be notified that a driver accepted the request and should receive an estimated time of arrival. Once the ambulance driver drops the user to the hospital, they should be able to mark the request as complete.

**Map View (Stretch Goal)**

- Users should be able to view a map of nearby ambulance drivers. This should be similar to Uber's map of nearby drivers.

---

**Timeline**

| Week   | Plan                                                                                                                                                                                                                               |
|--------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Week 1 | - Onboard all developers onto tech stack and git / GitHub workflow - Design database and API schema by creating design docs - Set up database and server - Complete High Fidelity Prototype                                        |
| Week 2 | - Create frontend for User Registration - Add users to the database through the frontend - Research location permissions - Be able to successfully retrieve a user's location                                                      |
| Week 3 | - Create frontend for requesting help - Create frontend for accepting and completing request - Create a backend service to find nearest location of a driver that is not flagged as busy - Research push notifications             |
| Week 4 | - Connect frontend to database to be able to successfully request, accept, and complete help - Add push notifications for drivers - Add open navigation via Google / Apple Maps - If there is time, complete the maps stretch goal |
| Week 5 | - Document all code both inline and via GitHub WIki - Deploy project via Expo and Heroku - Create project presentation                                                                                                             |

---

**Project Workflow**

In our project workflow, we will be leveraging the GitHub platform. The Project Manager will create issues for new features and bug resolutions. Developers will review each other's pull requests. After two approvals, pull requests can be merged into the master branch. Every morning, developers will post a standup in slack on what they accomplished the previous day and what they hope to accomplish today.

---
