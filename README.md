
# MealPlanner

MealPlanner is a SwiftUI + UIKit iOS application that helps users plan meals based on the ingredients they already have. It intelligently recommends dishes, generates shopping lists, and offers step-by-step cooking instructions — all tailored to user preferences like diet, difficulty, and nutrition goals.

---

## 🧠 Core Features

- ✅ **Ingredient-Based Dish Suggestions**
- ✅ **Search & Filter**: by prep time, difficulty, veg/non-veg
- ✅ **Favorites**: save recipes for offline use
- ✅ **Meal Plan Builder**: drag-and-drop interface for planning meals across a week
- ✅ **Smart Cooking Guide**: step-by-step cooking instructions with built-in timers
- ✅ **Nutrition Insights**: expandable macros, vitamins, and more
- ✅ **Substitution Suggestions**: see ingredient swaps and nutrition impact
- ✅ **Auto Shopping List**: based on planned meals
- ✅ **User Preferences**: dietary settings, cuisine types, cook time caps

---

## 📱 App Screens (UI Navigation)

| Screen            | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| **Home**          | Search dishes, enter pantry inventory, view suggestions           |
| **Dish Detail**   | View full recipe info, nutrition, and cooking steps               |
| **Cooking Mode**  | Timer-based steps like “Bake at 180°C for 40 minutes”             |
| **Meal Plan**     | Build and customize weekly meal plans                             |
| **Favorites**     | Store and access saved recipes                                    |
| **Shopping List** | Auto-generated list from meal plan                                |
| **Settings/Profile** | Manage preferences, data, and dietary filters                 |

---

## 🧭 Navigation Structure

- 🏠 Home
- 📅 Meal Plan
- ⭐ Favorites
- 🛒 Shopping List
- ⚙️ Profile/Settings

---

## 🏗 Project Architecture (MVVM + SwiftUI/UIKit)

```
MealPlanner/
├── Models/             # Data models (Meal, Ingredient, etc.)
├── ViewModels/         # Business logic & state (MealViewModel, PlanViewModel)
├── Views/              # SwiftUI Views
├── Controllers/        # UIKit ViewControllers (bridging or legacy)
├── App/                # AppDelegate, SceneDelegate, Storyboards
├── Assets.xcassets     # App icons, images
├── Info.plist
```

---

## 🔗 External APIs Used

- [Spoonacular API](https://spoonacular.com/food-api) – Recipe, nutrition, and substitution data  
- [TheMealDB](https://www.themealdb.com/api.php) – Free recipe source (backup/fallback)

---

## 🧪 Testing

- Unit Testing: Meal logic, filtering, and planner operations
- UI Testing: Navigation flow, step execution, edge cases

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/MealPlanner.git
   ```

2. Open in Xcode:
   ```bash
   open MealPlanner.xcodeproj
   ```

3. Add API keys in `Secrets.swift` (not tracked in version control):
   ```swift
   let SPOONACULAR_API_KEY = "your_api_key"
   ```

4. Run the project on simulator or device.

---

## 🗂 Tech Stack

- Swift 5
- SwiftUI + UIKit Hybrid
- MVVM Architecture
- URLSession for API calls
- JSON Decoding
- CoreData or UserDefaults for offline storage (favorites/plan)

---

## 🧠 Future Plans

- 🧾 Barcode Scanner for adding ingredients
- ☁️ CloudKit sync for meal plans
- 🗣 Voice-guided cooking mode
- 🧠 AI-enhanced recipe recommendation engine

---

## 👨‍🍳 Author

**Ashmit Jain**  
[Portfolio](https://ashmit27j.wixstudio.com/my-blogs)  
[GitHub](https://github.com/ashmit27j)  
[HackerRank](https://www.hackerrank.com/profile/ashmit)

---

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
