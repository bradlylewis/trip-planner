# 🗺️ TripTactix – Smart Group Trip Planner

A collaborative trip planning tool built with **Vue 3** and **Supabase** that helps small groups vote on trip details, build daily itineraries, preview maps, and stay organized—all in one place.

## 🛠 Tech Stack

- **Frontend:** Vue 3 (Composition API), Vue Router, Tailwind CSS, Pinia  
- **Drag & Drop:** Vue Draggable (Sortable.js)  
- **Maps:** Google Maps API  
- **Backend:** Supabase (PostgreSQL, Auth, Realtime)  
- **Serverless Logic:** Google Cloud Functions  
- **Optional AI:** OpenAI API for itinerary suggestions  

## 🚀 Features

| Feature                  | Description                                                              |
|--------------------------|--------------------------------------------------------------------------|
| 🧳 Trip Creation          | Set destination, proposed dates, and invite group members                |
| 🗳️ Voting System          | Vote on dates, lodging, restaurants, and activities                      |
| 📅 Itinerary Builder      | Drag-and-drop schedule for each day of the trip                          |
| 📝 Shared Notes & Tasks   | Create shared checklists and reminders for trip tasks                    |
| 🗺️ Map Integration        | Preview locations and routes via Google Maps                             |
| 📤 Export Itinerary       | Send final trip details via PDF or email                                 |
| 💡 AI Assistant (Optional)| Suggest activities based on destination and group theme                  |
| 💸 Budget Tracker (Bonus) | Estimate per-person and group trip costs                                 |
| 📷 Memory Vault (Bonus)   | Upload and save trip photos as a post-trip scrapbook                     |

## 📦 Folder Structure

triptactix/  
├── public/  
├── src/  
│   ├── components/  
│   ├── pages/  
│   ├── stores/ (Pinia)  
│   ├── composables/  
│   ├── services/ (Supabase + Cloud Functions)  
│   └── App.vue  
├── .env  
├── functions/ (Cloud Functions)  
└── README.md  

## ⚙️ Setup Instructions

1. **Clone the repo**  
   `git clone https://github.com/yourusername/triptactix.git && cd triptactix`

2. **Install dependencies**  
   `npm install`

3. **Configure environment variables**  
   Create a `.env` file and add your Supabase, Google Maps, and OpenAI keys:

```
VITE_SUPABASE_URL=...
VITE_SUPABASE_ANON_KEY=...
VITE_GOOGLE_MAPS_API_KEY=...
VITE_OPENAI_API_KEY=... (optional)
```

4. **Run the app**  
   `npm run dev`

5. **Deploy**  
   Use Vercel, Netlify, or Firebase Hosting for frontend  
   Use Google Cloud Functions for voting + reminder logic

## 📸 Screenshots

_Add images of trip creation, voting, itinerary view, and map integration._

## 📄 License

MIT — build on it, remix it, and help people plan better trips.
