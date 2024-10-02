# Dynamic Dashboard / Widget System

This project is designed to build a dynamic dashboard or widget system that allows users to manage categories and widgets efficiently. Users can add or remove widgets from categories, search through available widgets, and customize the dashboard as needed.

project is running in Vite engine use **npm run dev** to run the project locally

# Deployed link
https://accuknow-dashboard.vercel.app/

# Github Link
https://github.com/Dav310/Accuknow-Dashboard

## Features

- **Category and Widget Management**: 
  - Users can add new categories and assign multiple widgets to each category.
  - Widgets can be dynamically added or removed from categories.

- **Add Widget**:
  - Users can add a widget by specifying the widget name and text.
  - The widget will be added to the selected category.

- **Remove Widget**:
  - Users can remove a widget by clicking the cross icon on the widget.
  - Alternatively, users can go to the category management section and uncheck widgets from the category list.

- **Search Functionality**:
  - Users can search through the list of all available widgets.

## JSON Structure

The following JSON structure is used to represent the categories and widgets in the system:

```json
{
  "categories": [
    {
      "id": "c1",
      "name": "CSPM Executive Dashboard",
      "widgets": [
        {
          "id": "w1",
          "name": "Widget 1",
          "text": "This is some random text for Widget 1"
        },
        {
          "id": "w2",
          "name": "Widget 2",
          "text": "This is some random text for Widget 2"
        }
      ]
    },
    {
      "id": "c2",
      "name": "Security Dashboard",
      "widgets": [
        {
          "id": "w3",
          "name": "Widget 3",
          "text": "This is some random text for Widget 3"
        }
      ]
    }
  ]
}
