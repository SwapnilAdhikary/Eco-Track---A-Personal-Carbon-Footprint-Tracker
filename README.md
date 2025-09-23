# EcoTrack - A Personal Carbon Footprint Tracker:
A Carbon Footprint Tracker to Manage and Calculate your Carbon Emission

-----------------------------------

This is the place where you can successfully and accurately track your personal carbon footprints produced in your everyday life...

	Read the following for clear instructions:

🌍 EcoTrack – Personal Carbon Footprint Tracker

🚩 *Problem:*

Most people want to live sustainably but lack simple, engaging tools to understand the impact of their daily choices. The problem EcoTrack addresses is the gap between awareness and action in personal carbon footprint tracking—individuals know climate change is urgent, but they don’t know how much their habits (like travel, food, or energy use) contribute. EcoTrack makes this problem visible and actionable by letting users log activities, visualize their carbon breakdown in real time, and discover small, trackable ways to reduce their footprint.


---

💡 *Solution:*

EcoTrack provides a simple yet powerful platform for individuals to measure, visualize, and reduce their carbon footprint. Users can log everyday activities—such as commuting, electricity use, or meals—and instantly see their impact through intuitive charts. The app calculates emissions dynamically, presents a clear breakdown of sources, and offers actionable eco-friendly suggestions (like choosing biking over driving or trying a plant-based meal). With a lightweight backend and real-time dashboard, EcoTrack turns sustainability into an interactive, trackable experience. It not only raises awareness but also empowers users to make informed lifestyle changes, bridging the gap between knowledge and action.


---

⚙️ *Tech Stack:*

Frontend: React, Tailwind CSS, Recharts, shadcn/ui

Backend: Node.js, Express, SQLite

Deployment: Vercel (frontend), Render/Railway (backend)



---

🖥️ *Running the Project:*

Backend:

cd ecotrack-backend
npm install
node index.js

Runs on http://localhost:4000

Frontend:

cd ecotrack-frontend
npm install
npm start

Runs on http://localhost:3000


---

✅ *Testing Instructions:*

To test EcoTrack, start the backend with node index.js (you should see “EcoTrack backend running at http://localhost:4000”) and verify the API using Postman or curl: a GET /activities request should return an empty list at first, a POST /activities with a JSON body like {"activity":"Car Travel","value":50} should confirm successful logging, and another GET should show the saved entry; optionally test DELETE /activities/:id to remove it. Then run the frontend with npm start and open http://localhost:3000, where adding activities updates the pie chart in real time. Try logging multiple types of activities to see different chart slices, refresh to confirm data persists from the backend, and test invalid inputs (like empty fields) to ensure they are not saved. For deployment, update the frontend API URL to your hosted backend and repeat the same steps to confirm the full stack works online.


---

🚀 *Future Enhancements:*

Leaderboard to compare EcoScores with friends.

Gamified challenges to encourage sustainable habits.

Integration with IoT devices (e.g., smart meters, fitness trackers).

Mobile app version for quick logging on the go.



---

👥 _**Swapnil Adhikary, Class 8, INDIA**_

EcoTrack is built as a hackathon-ready full-stack project combining sustainability and technology to inspire climate-conscious living.



THANK YOU FOR LETTING ME BE A PART OF THIS PROJECT!!! 
-----------------------------------

**ENJOY THIS SMALL CREATION OF MINE!!!**
