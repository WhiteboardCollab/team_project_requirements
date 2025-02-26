# Software Requirements Specification (SRS) for WhiteBoard Collab

## 1. Introduction
The purpose of the WhiteBoard Collab software is to integrate a real-time collaborative whiteboarding feature within popular online meeting platforms such as Zoom and Microsoft Teams. This feature will enable users to brainstorm, visualize ideas, and communicate effectively using interactive visual tools. The intended audience includes students, professionals, and teams who rely on virtual meetings for collaboration.

## 2. Functional Requirements
The functional requirements describe the essential features and functions that the system must be able to perform. The full list of functional requirements is available in the following view:

- [Functional Requirements View](https://github.com/orgs/WhiteboardCollab/projects/5/views/7?visibleFields=%5B%22Title%22%2C%22Assignees%22%2C%22Status%22%2C171667321%5D&filterQuery=types%3AFunctional+types%3A)

### **Functional Requirements Include:**
1. Enable real-time collaborative drawing and sketching.
2. Provide shape presets and text annotation tools.
3. Implement visual "ping" indicators for focus areas.
4. Allow multiple users to interact simultaneously.
5. Ensure seamless integration with existing video conferencing platforms (Zoom and Teams).
6. Provide user roles and permissions (e.g., presenter, viewer, editor).

## 3. Non-Functional Requirements
Non-functional requirements specify the performance, security, and other operational constraints of the system. The full list of non-functional requirements is available in the following view:

- [Non-Functional Requirements View](https://github.com/orgs/WhiteboardCollab/projects/5/views/10?filterQuery=types%3A%22Non-Functional%22+types%3A)

### **Non-Functional Requirements Include:**
1. The system should have a user-friendly and intuitive interface.
2. Performance should allow real-time updates with minimal latency.

## 4. System Architecture
The system is an extension of existing online meeting platforms, bridging the gap between standard screen-sharing features and real-time collaborative brainstorming tools. It eliminates the need for third-party applications by integrating directly into Zoom and Microsoft Teams. This integration will provide an intuitive interface for users to draw, annotate, and interact visually.

## 5. Data Design
The data will be primarily session-based, with user interactions and drawings stored temporarily during the meeting and optionally saved to cloud storage based on user preferences. Each session will handle real-time data synchronization to ensure smooth collaboration.

## 6. Interface Design
The interface will consist of:
- A whiteboard area for freeform drawing and annotations.
- A toolbar with shape presets (lines, circles, squares), text annotation tools, and other collaborative tools.
- A control panel for user roles (presenter, editor, viewer).
- A focus indicator ("ping") for highlighting areas of interest during collaboration.

## 7. Performance Requirements
The system must allow real-time updates with minimal latency to ensure a smooth collaborative experience. Performance should scale effectively as more users join the session.

## 8. Security Requirements
The system should comply with security standards for user data protection, including encryption during real-time collaboration and compliance with privacy regulations for online meeting platforms.

## 9. Constraints
We are still trying to determine the limitations of Zoom and Microsoft Teams APIs and how to integrate our technology into existing ones. Additionally, limitations may arise from the platform's handling of third-party integrations.

## 10. Assumptions and Dependencies
- Users will have a stable internet connection to support real-time collaboration.
- The meeting platforms (Zoom/Teams) will continue to support third-party integrations.

## 11. Glossary
- **Collaborative whiteboarding**: A tool that allows multiple users to draw and annotate on a shared digital whiteboard in real time.
- **User roles**: Permissions that define what actions a user can perform (e.g., presenter, editor, viewer).
- **Latency**: The time delay between an action performed by a user and its reflection on other users' screens.
