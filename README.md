# Weekly Meal & Grocery Planner

A client-side Weekly Meal & Grocery Planner designed to help you organize your weekly menu, manage a custom recipe library, and aggregate grocery lists all without needing an account or external server.

Hosted live on **[GitHub Pages](http://misslilmango.github.io/meal-planner)**.

---

## Key Features

* **7-Day Interactive Schedule:** Assign recipes to any day of the week, shuffle single days, or use **Autofill** to randomize your weekly meal rotation. Past days are shaded and today is highlighted automatically.
* **Recipe Library:** Store and organize recipes with custom categories (*Sheet Pan, Slow Cooker, Soup/Stew, Instant Pot, Salad, Quick Bite, and more*), tags, and instructions.
* **Smart Grocery List & Filters:** Ingredients from your scheduled meals automatically aggregate into a shopping list sorted by. Toggle scopes between **Full Week**, **Rest of Week**, or **Today Only**.
* **Pantry & Staples:** Archive ingredients you already own so they drop off your active shopping list, or add custom household staples on the fly.
* **Kitchen Cook Mode:** Open any meal in full-screen mode to view ingredients and cooking steps. Includes a built-in screen awake lock so your phone or tablet doesn't go to sleep while cooking.

---

## How the Memory Works

This application runs 100% in your browser using Local Browser Storage (`localStorage`). 

* **Data Privacy:** All of your recipes, weekly schedules, checked-off grocery items, and pantry stashes are saved privately inside your browser device. No data is ever sent to an external server.
* **Clearing Data:** Clearing your browser site data or cache will reset the planner back to a blank slate.

---

## Backup & Restore (Import / Export)

Because data is stored locally in your browser, you can easily transfer or back up your planner across different devices using the built-in backup tools:

* **Backup (Export):** Click the **Backup** button in the top navigation bar to download a small `.json` file containing your recipe library, schedule, and settings to your computer or phone.
* **Restore (Import):** Click the **Restore** button and upload a previously saved `.json` file to load your recipes and settings. This is great for moving your planner between devices or creating manual archives.

---

## Built With

* [Tailwind CSS](https://tailwindcss.com/)
* [FontAwesome](https://fontawesome.com/) for icons
* JavaScript & HTML5

---

## License

This project is open source. Feel free to customize it and make it your own!
