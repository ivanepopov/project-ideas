>[!Prompt]
>Structure a new coding project to be made by a very small group of people. Hosted on github, with a well structured file tree, which would be pleasant to recruiters. Provide a large variety of features to add more depth to the project. Also, provide information on the skills, libraries, etc. that will be needed. Choose a language of your choice.

**Project Name:** DreamJournal

**Tagline:** "A digital dream journal for recording, analyzing, and understanding your dreams."

**GitHub Repository Structure:**

1. **README.md:** A clear and concise description of the project, its goals, and the technologies used.
2. **docs/**
        * **manual.pdf:** User manual for DreamJournal
        * **technical_guide.pdf:** Technical guide for developers
3. **src/**
        * **core/**
                + **dreamjournal.cpp:** Implementation of DreamJournal core functionality
                + **database.cpp:** Implementation of database management system (using SQLite)
        * **utils/**
                + **nlp_tools.cpp:** Implementation of Natural Language Processing tools (e.g., sentiment analysis, keyword
extraction)
                + **image_processing.cpp:** Implementation of image processing and analysis tools (for extracting emotions from
dreams)
4. **tests/**
        * **unit_tests/**: Unit tests for individual components
        * **integration_tests/**: Integration tests for entire system
5. **utils/**
        * **config.h:** Configuration file for DreamJournal settings and other parameters

**Core Features:**

1. **Dream Recording:** Implement a feature that allows users to record their dreams, including audio and text
notes.
2. **Data Analysis:** Develop a system that analyzes users' dream data, providing insights into recurring themes,
emotions, and symbols.
3. **Emotion Tracking:** Include an emotion tracking feature that estimates the emotional state of a user during
their dream based on facial expressions and tone of voice.

**Additional Features:**

1. **Personalized Recommendations:** Provide users with personalized recommendations for improving sleep quality,
reducing stress, and enhancing dream recall.
2. **Community Forum:** Develop a community forum where users can share their dreams, discuss recurring themes,
and connect with others who share similar interests.
3. **Mindfulness Exercises:** Include mindfulness exercises and meditation techniques to help users relax and
prepare for sleep.

**Skills and Libraries:**

1. **C++14 features:** Utilize modern C++ language features, such as auto, range-based for loops, and smart
pointers.
2. **SQLite library:** Use SQLite library for database management system (for storing user data).
3. **NLTK library:** Implement Natural Language Processing tools using the NLTK library (for sentiment analysis,
keyword extraction, etc.).
4. **OpenCV library:** Utilize OpenCV library for image processing and analysis (for extracting emotions from
dreams).

**Technologies:**

1. **Qt Framework:** Use the Qt framework for creating a user-friendly interface.
2. **JSON library:** Implement JSON serialization and deserialization for storing and retrieving user data.

**Skills Needed:**

1. Proficiency in C++14
2. Experience with database management systems (using SQLite)
3. Familiarity with Natural Language Processing tools (using NLTK)
4. Knowledge of image processing and analysis techniques (using OpenCV)
5. Experience with Qt Framework for creating user-friendly interfaces.

**Tools:**

1. **GitHub:** Host the project on GitHub.
2. **Visual Studio Code:** Use Visual Studio Code as the IDE for coding and debugging.
3. **Qt Creator:** Utilize Qt Creator for designing and building the interface.

This project combines natural language processing, image processing, and database management to create a unique
digital dream journal. The skills needed for this project include proficiency in C++14, experience with database
management systems, familiarity with NLP tools, knowledge of image processing techniques, and expertise with Qt
Framework.