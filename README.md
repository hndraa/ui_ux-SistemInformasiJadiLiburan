# SI JALI — Sistem Informasi Jadi Liburan

UI / UX | WEB APP | FIGMA

SI JALI (Sistem Informasi Jadi Liburan) is a web-based tourism information system concept designed to help users discover tourist destinations, access destination information, and plan their trips through an intuitive user interface and interactive prototype.

## 01. Project Overview

### Project Description

SI JALI is a web application UI/UX design project developed to improve how users discover tourist destinations and access travel information. The proposed system brings destination recommendations, destination details, weather conditions, visitor-density information, facilities, and user reviews into one platform.

The project also considers the needs of destination managers and administrators who maintain destination information and manage user-generated content.

### Background

Tourists may have difficulty finding reliable and up-to-date information when planning a trip. Uncertain weather conditions, crowded destinations, and incomplete information about facilities can affect travel decisions and lead to disappointing experiences.

SI JALI proposes a centralized web-based information system to make destination information more accessible and support better-informed travel planning.

### Objectives

- Simplify the process of finding and exploring tourist destinations.
- Provide information about destination facilities, operating hours, descriptions, and contact details.
- Present weather and visitor-density information to support travel planning.
- Provide access to maps and directions through Google Maps.
- Enable users to submit ratings, reviews, comments, and images.
- Support destination managers in updating destination information.
- Support administrators in managing destination-manager data and moderating user reviews.

### Problem Statement

Tourists may need to consult multiple sources to find destination information and may not know the latest weather or visitor conditions before arriving. Meanwhile, destination managers need a way to communicate current information to potential visitors.

### Proposed Solution

SI JALI presents a web-based interface that centralizes destination discovery and travel information. Users can browse recommendations, search by keywords or categories, view destination details, access navigation, and explore reviews. The proposed system also defines management functions for destination managers and administrators.

### Key Features

- **Authentication:** Sign-up, login, and logout.
- **Home Page:** Destination recommendations, including nearby and popular destinations.
- **Destination Discovery:** Browse destinations by categories such as beaches, waterfalls, and mountains.
- **Search:** Find destinations using keywords.
- **Destination Details:** View destination descriptions, images, facilities, weather information, distance, and estimated travel time.
- **Visitor Density:** Display destination crowd-level indicators.
- **Navigation:** Open Google Maps directions for a selected destination.
- **Ratings and Reviews:** Read user feedback and submit ratings, comments, and images.
- **Destination Recommendations:** Allow users to recommend additional destinations.
- **User Profile:** Access profile settings, travel history, and bookmarks.
- **Destination Management:** Enable destination managers to add, update, or remove destination information as defined in the system design.
- **Administration:** Support user and destination-manager management and review moderation.

### System Roles

| Role | Main Responsibilities |
|---|---|
| Guest | Explore destination information without signing in; review submission is restricted. |
| User | Search for destinations, view details, and submit reviews. |
| Destination Manager | Maintain destination information and provide updates about destination conditions. |
| Administrator | Manage destination-manager data, destination information, and user reviews. |

### Design Scope

This repository showcases the UI/UX design and prototype of the SI JALI web-based information system, along with supporting system analysis and design documentation.

The project reports include requirements analysis, SWOT analysis, fishbone analysis, fact-finding methods, flow maps, system architecture, Data Flow Diagrams (DFD), a use case diagram, and an Entity Relationship Diagram (ERD).

The repository does not claim that the proposed system has been implemented as a fully functional web application.

## 02. Tech Stack

| Category | Technology / Tool |
|---|---|
| UI/UX Design | Figma |
| Interface Prototyping | Figma |
| System Modeling | Use Case Diagram, DFD |
| Database Modeling | Entity Relationship Diagram (ERD) |
| Project Documentation | PDF |

**Implementation note:** This is a design-focused project. No frontend framework, backend technology, programming language, or production database is claimed as implemented.

## 03. Screenshots / Results

This section presents the SI JALI interface concept and supporting system-design artifacts.

### 3.1 Authentication

The authentication interface presents sign-up and login flows. The documented concept includes authentication using username and password, with Google and Facebook login options described in the prototype documentation.

![SI JALI Authentication](screenshots/authentication.png)

### 3.2 Home Page and Destination Recommendations

The home page presents destination recommendations, including nearby destinations, popular destinations, and themed recommendations. It provides navigation to the main sections of the website.

![SI JALI Home Page](screenshots/home-page.png)

### 3.3 Destination Discovery and Search

The discovery interface allows users to explore destinations by category and search for destinations using keywords.

![SI JALI Destination Discovery](screenshots/destination-discovery.png)

### 3.4 Destination Details

The destination detail page presents information such as destination images, descriptions, facilities, weather conditions, distance, estimated travel time, and visitor-density indicators.

![SI JALI Destination Details](screenshots/destination-details.png)

### 3.5 Maps and Navigation

The proposed navigation flow allows users to open Google Maps directions from a selected destination.

![SI JALI Maps and Navigation](screenshots/maps-navigation.png)

### 3.6 Ratings and Reviews

The review interface supports the presentation of ratings, comments, and images submitted by users to help other visitors evaluate destinations.

![SI JALI Ratings and Reviews](screenshots/ratings-reviews.png)

### 3.7 User Profile and Settings

The profile section includes profile editing, travel history, bookmarks, and logout. The settings section provides access to help and about-us information.

![SI JALI User Profile](screenshots/user-profile.png)

### 3.8 Use Case Diagram

The use case diagram documents interactions between users, destination managers, and administrators, including destination discovery, viewing details, submitting reviews, and managing destination information.

![SI JALI Use Case Diagram](screenshots/use-case-diagram.png)

### 3.9 Entity Relationship Diagram (ERD)

The ERD describes the proposed data entities and their relationships, including users, administrators, destination managers, reports, and tourist destinations.

![SI JALI Entity Relationship Diagram](screenshots/erd.png)

### Results

The project documents a proposed web-based tourism information system through interface prototypes and system-design artifacts. The design focuses on destination discovery, travel information, navigation, reviews, and destination-information management.

## 04. Installation & Usage

### Prerequisites

- A web browser.
- Access to the SI JALI Figma design file or prototype.
- A Figma account if required by the sharing permissions.

Since this repository contains design artifacts rather than an implemented application, no package installation, build command, or application runtime is required.

### Project Structure

```text
├── README.md
├── screenshots/
│   ├── authentication.png
│   ├── home-page.png
│   ├── destination-discovery.png
│   ├── destination-details.png
│   ├── maps-navigation.png
│   ├── ratings-reviews.png
│   ├── user-profile.png
│   ├── use-case-diagram.png
│   └── erd.png
└── documentation/
    ├── tubes1-project-analysis.pdf
    ├── tubes2-system-design.pdf
    ├── tubes3-requirements-and-feasibility.pdf
    └── tubes4-prototype-and-modeling.pdf
```

*The filenames above are suggested repository names. Rename the files accordingly when adding them to GitHub.*

### Setup

**Step 1 — Clone the repository**

Replace the placeholder with the actual repository URL.

```bash
git clone [YOUR_GITHUB_REPOSITORY_URL]
```

**Step 2 — Open the project folder**

```bash
cd si-jali-web-ui-ux
```

**Step 3 — Review the documentation**

Open `README.md` to explore the project overview and screenshots. Open the PDF files in `documentation/` for the complete project reports.

### Accessing the Figma Prototype

1. Open the SI JALI Figma design file using the link below.
2. Review the available interface screens.
3. Open prototype mode to explore the interactions and navigation flows, if enabled.
4. Compare the prototype with the supporting diagrams and documentation in this repository.

**Figma Design / Prototype:** [Open SI JALI in Figma](https://www.figma.com/design/GslckSftzP5B2VjeeopRVG/Si-Jali?node-id=0-1&t=0K0pngSdWv6YqelD-1)

### Repository Contents

- `README.md` — project overview, features, screenshots, and usage instructions.
- `screenshots/` — exported interface screens and system diagrams.
- `documentation/` — supporting academic reports and design documentation.

---

**Project Domain:** UI / UX  
**Project Type:** Web App  
**Design Platform:** Figma  
**Source Code:** Not included
