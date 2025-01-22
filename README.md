<img width="80" src="https://github.com/AdenWhitworth/checkmate_Front-End/raw/master/src/Images/King%20Logo%20Black.svg" alt="Checkmate Logo">

# Checkmate

Welcome to the **Checkmate** project! This application is designed for chess enthusiasts to challenge friends, chat during matches, track their rankings, solve over 3,000 interactive puzzles, and hone their skills against various AI-powered bots. The project is structured into three interconnected repositories, each focusing on a core aspect of the application: **Frontend**, **backend**, and **AI**.

Explore each repository to learn more about the features, technologies, and implementation details that make Checkmate a unique and engaging chess platform.

## Table of Contents
- [Checkmate Demo](#checkmate-demo)
- [Front-End](https://github.com/AdenWhitworth/checkmate_Front-End)
- [Back-End](https://github.com/AdenWhitworth/checkmate_Back-End)
- [AI](https://github.com/AdenWhitworth/checkmate-AI)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## Checkmate Demo

The Checkmate application is live and can be accessed here: [Checkmate Demo](https://checkmateplay.com). You can explore all features of the game, including real-time gameplay, puzzles, chat, and rankings.

<img width="600" src="https://github.com/AdenWhitworth/aden_whitworth_portfolio/raw/master/src/Images/chess_demo.png" alt="Checkmate Demo">

### Test User Credentials

Try out the app using the following demo accounts:

- **Emails:** demo1@gmail.com & demo2@gmail.com
- **Password:** PortfolioDemo1!

>**Note**: You can even play against yourself by opening the application in two separate browser windows.

## Front-End: [Checkmate Front-End](https://github.com/AdenWhitworth/checkmate_Front-End)

The web-based user interface for the Checkmate application, built with React, allows players to compete against live opponents, chat in-game, track their rankings, practice chess strategies with interactive puzzles, and compete against human-like AI bots.

## Back-End: [Checkmate Back-End](https://github.com/AdenWhitworth/checkmate_Back-End)

The Node.js backend API manages active chess games (human and bot), user authentication, in-game chat, interactive puzzles, and ELO ranking systems. It ensures smooth, real-time gameplay and communication through WebSockets integration.

## AI: [Checkmate AI](https://github.com/AdenWhitworth/checkmate-AI)

The AI component of Checkmate leverages advanced machine learning models developed using TensorFlow and Python to deliver dynamic, skill-matched gameplay for users. By training specialized transformer models for the opening and midgame phases and integrating the Lichess 7-piece endgame tablebase, the AI provides strategic and adaptive gameplay across all stages of a chess match. Specific models were created to simulate opponents at various ELO ranges, ensuring a tailored experience for players of all skill levels. Exported in ONNX format, these models seamlessly integrate with the backend, enabling smooth and responsive gameplay.

## Technologies Used

- **React**: A powerful JavaScript library for building user interfaces, enabling the development of dynamic and responsive web applications.
- **TypeScript**: A strongly typed superset of JavaScript that enhances code quality and provides better tooling and type safety during development.
- **HTML/JSX**: The foundational markup language used for structuring the components of the React application, ensuring semantic and accessible content.
- **CSS**: Styles the application with a modern aesthetic, allowing for flexible and maintainable design.
- **React Router**: A library that enables dynamic routing in the application, providing a seamless navigation experience for users.
- **MUI (Material-UI)**: A popular React component library that implements Google's Material Design, providing pre-designed components for charts, gauges, and more, enhancing visual consistency.
- **Socket.IO**: A library that facilitates real-time, bidirectional communication between clients and servers, crucial for features like live updates and notifications.
- **React-chessboard.js**: A lightweight and flexible chessboard library designed for React, providing an intuitive interface for displaying and interacting with chess positions in your React applications.
- **Chess.js**: A JavaScript library that implements chess mechanics, enabling the creation of legal move generation, validation, and game state management in a chess application.
- **uuid.js**: A library used to generate unique identifiers (UUIDs), essential for creating distinct and secure references for users, games, and various entities in web applications.
- **Node.js**: Backend runtime environment for executing JavaScript on the server.
- **Express.js**: Web framework for building the RESTful API.
- **JWT (JSON Web Tokens)**: Used for secure authentication.
- **onnxruntime-node**:  A high-performance runtime for executing ONNX models in Node.js, enabling seamless integration of AI-powered features such as chess move predictions and strategic analysis into the backend.
- **Firebase**:
  - **Authentication**: Provides secure sign-in via various methods, including email/password, Google, etc.
  - **Firestore**: A NoSQL database optimized for real-time data storage and synchronization.
  - **Admin**: Firebase Admin SDK is used for server-side operations like managing users, securely accessing Firebase databases, and performing other privileged tasks such as setting up custom claims for user roles and managing user accounts programmatically.
- **Chess**: A python library for validating and manipulating chess moves, ensuring the legality of each action during gameplay.
- **Keras**: A high-level neural network API that simplifies the building and training of machine learning models, used here for rapid development of DNN and CNN models.
- **Matplotlib**: A Python library for creating visualizations, such as accuracy and loss graphs, to analyze model performance.
- **NumPy**: A fundamental Python library for numerical computations, particularly useful for manipulating game data and creating training datasets.
- **ONNX**: (Open Neural Network Exchange) A format for exporting and integrating machine learning models across different frameworks, enabling smooth backend deployment.
- **Pandas**: A Python library for data manipulation and analysis, used to preprocess and structure PGN game data.
- **Python**: The primary programming language for the project, powering all data processing, model training, and backend integration.
- **Scikit-learn (SKLearn)**: A machine learning library for preprocessing data, evaluating models, and implementing supplementary algorithms like scaling and validation.
- **TensorFlow**: An end-to-end machine learning framework used for building, training, and fine-tuning AI models, including transformers and neural networks.
- **Linchess Database**: Open-source database containing over 5 million chess puzzles with solutions, used to power interactive puzzle features at varying skill levels.
- **Cudatoolkit**: A toolkit that provides libraries and tools for GPU-accelerated computing, enabling efficient execution of TensorFlow models on NVIDIA GPUs.
- **CUDNN**: NVIDIA’s CUDA Deep Neural Network library, used to optimize the performance of deep learning frameworks like TensorFlow during model training and inference.
- **Conda**: A versatile package manager that simplifies the environment setup and dependency management for Python libraries used in the project.
- **Tqdm**: A Python library for generating progress bars, providing real-time feedback during data processing and model training.
- **Onnxoptimizer**: A library for optimizing ONNX models by reducing size and improving inference speed without compromising accuracy.
- **Onnxruntime**: A high-performance runtime for executing ONNX models, enabling efficient inference of trained models during gameplay.
- **Tf2onnx**: A conversion tool that seamlessly exports TensorFlow models into the ONNX format, facilitating integration with the Checkmate backend.

## Getting Started
Instructions for setting up each project can be found in their respective repositories.

## Contribution Guidelines
Feel free to open issues or submit pull requests for any improvements or bug fixes!

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
