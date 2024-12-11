# Campus Complaint Resolution Portal

The **Campus Complaint Resolution Portal** is a user-friendly tool designed to help students quickly find the appropriate contacts for resolving campus-related issues. Whether it's a problem with hostel maintenance, academics, placements, or other campus facilities, this portal streamlines the resolution process by providing relevant contact information and estimated resolution times.

---

## Features

- **Text-Based Input**: Students can type their complaints, and the system uses an AI-powered algorithm to match the text to the most relevant department or contact.
- **Dropdown Selection**: Students can choose from predefined categories and problem statements for quick results.
- **Detailed Output**: Displays contact email or links, along with an estimated resolution time.
- **User-Friendly Interface**: Built with Streamlit for an intuitive and accessible user experience.

---

## How It Works

1. **Input Options**: Students can either type their complaints or select from a dropdown menu.
2. **Complaint Matching**: The system uses the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm to vectorize the complaint text and matches it to predefined complaints using the K-Nearest Neighbors (KNN) algorithm.
3. **Output Display**: Based on the match, the portal provides contact information and resolution time.

---

## Technology Stack

- **Programming Language**: Python
- **Framework**: Streamlit
- **Machine Learning**: TF-IDF Vectorizer and K-Nearest Neighbors (KNN) from Scikit-learn
- **Data Handling**: Pandas

---

## Dataset

The portal uses a predefined dataset that includes:
- **Divisions**: Hostel, Academics, Library, Placement, Mess/Cafeteria, etc.
- **Problem Statements**: Examples include "Room Maintenance Issue," "Wi-Fi Problems," "Exam Schedule Issues," etc.
- **Complaint Text**: Sample descriptions to match user input.
- **Contact Email**: Relevant contact information for each issue.
- **Resolution Time**: Estimated hours required to resolve each issue.

---


## Future Improvements

- Expanding the dataset to cover more scenarios.
- Integrating advanced NLP models like BERT for better text matching.
- Adding real-time notifications and feedback mechanisms.
- Deploying the application on a cloud platform for broader accessibility.

---

