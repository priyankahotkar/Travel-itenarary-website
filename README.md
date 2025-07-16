# Travel Itinerary Planner

A modern, interactive web application for planning, visualizing, and exporting beautiful travel itineraries. Users can enter trip details, add custom activities, flights, and transfers for each day, and generate a visually rich itinerary that can be downloaded as a PDF. [View live website](https://travel-itenarary-website.vercel.app/)

---

## ✨ Features

- **Multi-step Travel Form:** Collects all essential trip details, including destination, dates, group size, interests, accommodation, transport, and special requests.
- **Day-wise Planning:** Add multiple activities, flights, and transfers for each day of your trip.
- **Dynamic Itinerary Generation:** Combines user input with smart, destination-based suggestions for a rich, personalized itinerary.
- **Beautiful Web Display:** Modern, card-based UI with clear separation for each day, activities, flights, and transfers.
- **PDF Export:** Download your itinerary as a stylish PDF that closely matches the web display.
- **Responsive Design:** Works great on desktop and mobile.
- **Tech Stack:** React, TypeScript, Tailwind CSS, jsPDF.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/priyankahotkar/Travel-itenarary-website.git
   cd TravelIternary/project
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open in your browser:**
   ```
   http://localhost:5173
   ```

---

## 🗂️ Project Structure
project/
public/ # Static assets (logo, images)
src/
components/ # React components (Form, Itinerary, etc.)
utils/ # Utility functions (itinerary & PDF generators)
types/ # TypeScript types
index.css # Tailwind and global styles
App.tsx / App.jsx # Main app entry
package.json
tailwind.config.js
tsconfig.json
vite.config.ts


---

## 📁 Key Files

- **`src/components/TravelForm.jsx`**  
  Multi-step form for collecting all user trip details and day-wise plans.

- **`src/components/ItineraryDisplay.jsx`**  
  Displays the generated itinerary in a visually rich, card-based layout.

- **`src/utils/itineraryGenerator.ts`**  
  Merges user input with dynamic suggestions to create a complete itinerary.

- **`src/utils/pdfGenerator.ts`**  
  Generates a PDF that closely matches the web display, including all user and generated data.

---

## 🎨 Customization

- **Add More Destinations:**  
  Edit `src/utils/itineraryGenerator.ts` to add more destination data and suggestions.

- **Branding:**  
  Replace `public/logo.png` with your own logo.

- **Styling:**  
  Tweak `index.css` and `tailwind.config.js` for custom colors and fonts.

---

## 📄 Exporting as PDF

- Click the **Download PDF** button on the itinerary page.
- The PDF will include all days, activities, flights, transfers, and recommendations, styled to match the web view.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 🙏 Credits

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [lucide-react](https://lucide.dev/)

---

**Happy Travels!** 🌍✈️🗺️
