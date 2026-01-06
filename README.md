Newspaper Task – React News Portal

This project is a responsive news website built using React JS, Tailwind CSS, and DaisyUI.
It displays news in list/grid format with category-wise filtering and detailed news pages.

Installation Steps:

# Clone the repository
git clone https://github.com/sabbir347256/job_task-newspaper-.git

# Go to project directory
cd newspaper_task

# Install dependencies
npm install

# Run the project
npm run dev


Technologies Used

React JS – Component-based UI

Vite – Fast development build tool

Tailwind CSS – Utility-first CSS framework

DaisyUI – Tailwind-based UI components

React Router DOM – Routing & page navigation

Local JSON Data – News data source


Folder Structure:

src/
├── assets/
│
├── component/
│   ├── NesJson/
│   │   └── news.json
│   │
│   ├── Page/
│   │   ├── HomePageComponent/
│   │   │   └── FeatureNews/
│   │   │       └── FeatureNewsSection.jsx
│   │   │
│   │   ├── Home/
│   │   │   └── Home.jsx
│   │   │
│   │   ├── NavCategoryWiseNews/
│   │   │   └── CategoryWiseNews.jsx
│   │   │
│   │   └── NewsDetails/
│   │       └── NewsDetails.jsx
│   │
│   ├── Root/
│   │   └── Root.jsx
│   │
│   ├── Shared/
│   │   ├── Navbar.jsx
│   │   ├── Footer.jsx
│   │   └── Loading.jsx
│   │
│   └── ShareNewsCard/
│       ├── SingleNews.jsx
│       └── SingleNewsCard.jsx
│
├── image/
│
├── App.jsx
├── main.jsx
├── index.css
└── App.css

