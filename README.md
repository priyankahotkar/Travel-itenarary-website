
---

## Key Files

- **`src/components/TravelForm.jsx`**  
  Multi-step form for collecting all user trip details and day-wise plans.

- **`src/components/ItineraryDisplay.jsx`**  
  Displays the generated itinerary in a visually rich, card-based layout.

- **`src/utils/itineraryGenerator.ts`**  
  Merges user input with dynamic suggestions to create a complete itinerary.

- **`src/utils/pdfGenerator.ts`**  
  Generates a PDF that closely matches the web display, including all user and generated data.

---

## Customization

- **Add More Destinations:**  
  Edit `src/utils/itineraryGenerator.ts` to add more destination data and suggestions.

- **Branding:**  
  Replace `public/logo.png` with your own logo.

- **Styling:**  
  Tweak `index.css` and `tailwind.config.js` for custom colors and fonts.

---

## Exporting as PDF

- Click the **Download PDF** button on the itinerary page.
- The PDF will include all days, activities, flights, transfers, and recommendations, styled to match the web view.

---

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---


## Credits

- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [lucide-react](https://lucide.dev/)

---

**Happy Travels!** 🌍✈️🗺️
