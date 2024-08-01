# Meals App

This app provides users with a comprehensive guide to different meals, including recipes, ingredients, and preparation instructions. It is built using Flutter and offers a visually appealing, easy-to-navigate interface.

![ScreenRecording2024-07-31at8 24 38AM-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/67f3a226-8107-4166-b069-4424ba88c0e5)


## Features

- **Meal Categories**: Browse meals by different categories.
- **Meal Details**: View detailed information about each meal, including ingredients, steps, and preparation time.
- **Favorites**: Mark meals as favorites for quick access.
- **Responsive Design**: Adaptive layout that works on both Android and iOS devices.

## Technologies Used

- **Flutter**: For building the cross-platform mobile application.
- **Dart**: The programming language used for Flutter development.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Flutter SDK
- Android Studio or Visual Studio Code (with Flutter and Dart plugins installed)
- A physical or virtual device for running the app

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/LujainSaad/meals-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd meals-app
   ```
3. Install the required dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app on your desired device:
   ```bash
   flutter run
   ```

## Project Structure

```plaintext
meals-app/
│
├── lib/
│   ├── main.dart             
│   │
│   ├── models/               
│   │   └── meal.dart         
│   │
│   ├── screens/              
│   │   ├── categories_screen.dart  
│   │   ├── category_meals_screen.dart  
│   │   ├── filters_screen.dart     
│   │   ├── meal_detail_screen.dart 
│   │   └── tabs_screen.dart       
│   │
│   ├── widgets/              
│   │   ├── category_item.dart   
│   │   ├── meal_item.dart        
│   │   └── main_drawer.dart      
│   │
│   └── data/                 
│       ├── dummy_data.dart   
│       └── app_theme.dart    
│
└── pubspec.yaml
```            

## Contributing

Contributions to enhance the app are welcome. Please follow the standard fork-and-pull request workflow:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.


