# Smart India Hackathon 2025 – Workshop 
# Date: 19-05-2025
## Register Number: 212223040120
## Name: MURALIDHARAN M
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
Design a user-friendly platform (web and mobile) that:

Displays realistic 3D models of medicinal plants.

Provides multilingual educational content on each herb.

Allows users to take virtual tours grouped by health category (e.g., immunity, digestion).

Includes interactive elements like quizzes, bookmarks, and sharing options.

Uses AR/VR features for immersive learning experiences in supported devices.


## Proposed Solution / Architecture Diagram
[User Device]
     |
[React.js Frontend / Flutter Mobile App]
     |
[Node.js Backend API]
     |
[PostgreSQL Database] — Stores plant data, user notes, bookmarks
     |
[Firebase Auth] — User login and security
     |
[3D Model Viewer (Three.js / Unity WebGL)] — For plant exploration
     |
[Cloud Storage / CDN] — For videos, images, audio

![Screenshot 2025-05-19 214849](https://github.com/user-attachments/assets/e1ab5159-e305-46b0-97c7-8e66e9c0c4c4)


![Screenshot 2025-05-19 214957](https://github.com/user-attachments/assets/c27a3c8c-bdf5-4b4f-a33f-a625d7377342)


## Use Cases

| **User Type** | **Action**                                               | **Outcome**                                     |
| ------------- | -------------------------------------------------------- | ----------------------------------------------- |
| General User  | Clicks on a plant to view in 3D                          | Sees a rotatable, zoomable model with details   |
| Student       | Takes a guided tour on "Immunity Boosting Herbs"         | Learns about 5-10 relevant plants interactively |
| Practitioner  | Searches for "skin care" herbs                           | Filters and explores herbs with medicinal uses  |
| User          | Bookmarks a plant and takes notes                        | Saves content for later reference               |
| Visitor       | Uses AR mode to place plant in real-world space (mobile) | Experiences immersive learning                  |

## Technology Stack

| **Component**       | **Technology Used**                |
| ------------------- | ---------------------------------- |
| Frontend (Web)      | React.js                           |
| Mobile App          | Flutter                            |
| Backend API         | Node.js + Express                  |
| Database            | PostgreSQL                         |
| Authentication      | Firebase Authentication            |
| 3D Visualization    | Three.js / Unity WebGL             |
| Multimedia Handling | Cloudinary / Firebase Storage      |
| Search & Filter     | Elasticsearch or Custom Logic      |
| Hosting             | Render / Vercel / Firebase Hosting |

## Dependencies

| **Module/Service**               | **Duration** |
| -------------------------------- | ------------ |
| 3D Model Creation (20–30 plants) | 15 days      |
| Plant Data Collection & Curation | 10 days      |
| UI/UX Design                     | 7 days       |
| Multimedia (Video, Audio)        | 7 days       |
| Development & Integration        | 20 days      |
| Testing & Deployment             | 5 days       |
