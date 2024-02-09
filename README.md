# Watchix

Watchix is a streaming video website inspired by platforms like Netflix, designed to provide an immersive entertainment experience.

### Menu

-   [Features](##Features)
-   [Technologies Used](##Technologies-Used)
-   [Getting Started](##Getting-Started)
-   [Installation](###Installation)
-   [Contributing](###Contributing)
-   [License](###License)
-   [Contact](###Contact)

## Features

-   **Wide Range of Content**: Enjoy a diverse library of movies, TV shows, documentaries, and more.
-   **User Profiles**: Create multiple user profiles to personalize your viewing experience.
-   **Continue Watching**: Pick up where you left off with the "Continue Watching" feature.
-   **Recommendation Engine**: Receive personalized recommendations based on your viewing history.
-   **Search and Filter**: Easily find content using the search bar and apply filters for genre, release year, etc.
-   **Responsive Design**: Enjoy seamless streaming across devices, from desktop to mobile.

## Technologies Used

-   **Frontend**:

    -   React.js
    -   JavaScript
    -   HTML5
    -   CSS3 (with Tailwind CSS for styling)

-   **Backend**:

    -   Laravel
    -   PHP
    -   MySQL

-   **Other Tools and Libraries**:
    -   Vite for frontend bundling
    -   Laravel Mix for asset compilation
    -   Inertia.js for server-side rendering
    -   Axios for HTTP requests
    -   etc.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

-   Node.js
-   npm or yarn
-   Composer
-   PHP
-   MySQL

### Installation

1. Clone the repo
    ```sh
    git clone https://github.com/alifsuryadi/watchix.git
    ```
2. Navigate to the project directory
    ```sh
    cd watchix
    ```
3. Install dependencies
    ```sh
    npm install
    ```
4. Install Laravel dependencies
    ```sh
    composer install
    ```
5. Create a .env file by copying .env.example
    ```sh
    cp .env.example .env
    ```
6. Generate application key
    ```sh
    php artisan key:generate
    ```
7. Setup your MySQL database in the .env file
    ```sh
    DB_DATABASE=your_database_name
    DB_USERNAME=your_database_username
    DB_PASSWORD=your_database_password
    ```
8. Migrate the database
    ```sh
    php artisan migrate
    ```
9. Run the development server
    ```sh
    npm run dev
    php artisan serve
    ```

### Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

### License

Distributed under the MIT License. See LICENSE for more information.

### Contact

Project Link: https://github.com/alifsuryadi/watchix
