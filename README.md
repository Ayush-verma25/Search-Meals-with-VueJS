# Search Meals App

The **Search Meals App** is a Vue.js application that allows users to search for delicious recipes using the [MealDB API](https://www.themealdb.com/api.php). Users can browse meals by keyword, filter by category, view detailed recipe information, and save their favorite recipes.

## Features

- **Meal Search**: Search meals by ingredient, cuisine, or meal name.
- **Meal Categories**: Filter meals by category for easier browsing.
- **Recipe Details**: View ingredients, instructions, and preparation tips.
- **Favorites**: Save favorite meals for quick access.
- **Responsive Design**: Optimized for both desktop and mobile viewing.

## Tech Stack

- **Frontend**: Vue.js, Vue Router, Vuex
- **API**: The MealDB API
- **Styling**: CSS or TailwindCSS for responsive and user-friendly design

## Installation

Follow these steps to set up the project locally.

### Install Dependencies

```bash
npm install
```

### Set Up Environment Variables

1. Create a `.env` file in the root directory.
2. Add the following, replacing `<API_KEY>` with your API key from [MealDB](https://www.themealdb.com/api.php):
   ```env
   VUE_APP_MEALDB_API_URL=https://www.themealdb.com/api/json/v1/<API_KEY>
   ```
## Usage

1. **Search Meals**: Type a keyword or ingredient into the search bar to find relevant meals.
2. **Filter by Category**: Choose a category (e.g., Seafood, Vegetarian) to filter results.
3. **View Recipe Details**: Click on a meal to view ingredients, instructions, and images.
4. **Save Favorites**: Save meals to your Favorites list for easy access.

## API Integration

The app uses [TheMealDB API](https://www.themealdb.com/api.php) to fetch meal data, including search results, categories, and detailed recipe information. Ensure to set up your API key in the `.env` file as described.

## Contributing

Contributions are welcome! Please open an issue or pull request to suggest improvements or add new features.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to [TheMealDB](https://www.themealdb.com/) for providing the API used in this project.
