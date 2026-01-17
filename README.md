## React + vite + node 

### this is my project.
job-listing-app/
│
├── client/                     # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── jobs/
│   │   │   │   ├── JobCard.jsx
│   │   │   │   ├── JobList.jsx
│   │   │   │   ├── JobFilters.jsx
│   │   │   │   └── JobSearchBar.jsx
│   │   │   ├── ui/
│   │   │   │   ├── Button.jsx
│   │   │   │   └── Input.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── JobDetails.jsx
│   │   │   └── SavedJobs.jsx
│   │   ├── hooks/
│   │   │   ├── useJobs.js
│   │   │   └── useFilters.js
│   │   ├── lib/
│   │   │   └── supabaseClient.js
│   │   ├── styles/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server/                     # Node backend (optional but recommended)
│   ├── index.js
│   ├── routes/
│   │   └── jobs.js
│   ├── controllers/
│   │   └── jobsController.js
│   ├── services/
│   │   └── supabaseService.js
│   ├── middleware/
│   └── package.json
│
├── database/                   # SQL, schema, seed data
│   ├── schema.sql
│   ├── seed.sql
│   └── policies.sql
│
├── README.md
└── .env
