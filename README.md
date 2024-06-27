# Recipe Manager

## Overview

Recipe Manager is a WPF application that allows users to add, view, and filter recipes. It supports managing ingredients, steps, and filtering recipes based on certain criteria.

## Installation and Setup

1. **Clone the Repository:**

    ```sh
    git clone https://github.com/your-repo/recipe-manager.git
    cd recipe-manager
    ```

2. **Open the Project:**

    Open the `RecipeManager.sln` file in Visual Studio.

## User Manual

### Main Window

The main window of the application is divided into four tabs:

1. **Add Recipe**
2. **View Recipes**
3. **Display Recipe**
4. **Filter Recipes**

### Add Recipe Tab

In the "Add Recipe" tab, you can add a new recipe by following these steps:

1. **Enter Recipe Name:**
    - Type the name of the recipe in the "Recipe Name" text box.

2. **Add Ingredients:**
    - Enter the ingredient details in the respective fields:
        - Ingredient Name
        - Quantity
        - Unit
        - Calories
        - Food Group
    - Click the `Add Ingredient` button to add the ingredient to the recipe.

3. **Add Steps:**
    - Enter the step description in the "Step Description" text box.
    - Click the `Add Step` button to add the step to the recipe.

4. **Save Recipe:**
    - Click the `Save Recipe` button to save the recipe.

### View Recipes Tab

In the "View Recipes" tab, you can view all the saved recipes:

1. **Display Recipes:**
    - Click the `Display Recipes` button to display all recipes in the list box.

### Display Recipe Tab

In the "Display Recipe" tab, you can view the details of a specific recipe by following these steps:

1. **Enter Recipe Number:**
    - Enter the recipe number in the "Recipe Number" text box.

2. **Display Recipe:**
    - Click the `Display Recipe` button to display the details of the recipe in the text block.

### Filter Recipes Tab

In the "Filter Recipes" tab, you can filter recipes based on specific criteria:

1. **Enter Filter Criteria:**
    - Enter the ingredient names (comma-separated) in the "Ingredient Name" text box.
    - Enter the food group in the "Food Group" text box.
    - Enter the maximum calories in the "Maximum Calories" text box.

2. **Filter Recipes:**
    - Click the `Filter Recipes` button to display the filtered recipes in the list box.

### Troubleshooting

- **Invalid Recipe Number:**
    - Ensure the recipe number entered in the "Display Recipe" tab is within the valid range.
    
- **Field Validation:**
    - Ensure all required fields are filled correctly before adding ingredients or steps.
    
### Contact

For any issues or questions, please contact [your-email@example.com].

