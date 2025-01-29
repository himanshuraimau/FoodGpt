# FoodGPT

FoodGPT is an intelligent food recommendation system that uses machine learning to suggest restaurants based on user preferences and sentiment analysis.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Example Conversation](#example-conversation)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    cd FoodGPT
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the application:
    ```bash
    python Final_app.py
    ```

2. Follow the on-screen instructions to get restaurant recommendations.

## Example Conversation

1. **Greeting**:
   - You: `Hi!`
   - FoodBRO: `Hi! I'm your restaurant recommendation bot.`

2. **Request a Recommendation**:
   - You: `Can you recommend a restaurant?`
   - FoodBRO: `Sure! What type of cuisine are you in the mood for?`
   - You: `Italian`
   - FoodBRO: `And in which city are you located?`
   - You: `Agra`
   - FoodBRO: `Got it! Let me find some restaurants for you.`
   - FoodBRO: `Here are some top restaurants for Italian in Agra:`
     - (List of recommended restaurants)

3. **Request Best Food Items**:
   - You: `What are the best food items?`
   - FoodBRO: `Sure! What type of cuisine are you interested in?`
   - You: `Chinese`
   - FoodBRO: `And in which city are you located?`
   - You: `Agra`
   - FoodBRO: `Got it! Let me find the best food items for you.`
   - FoodBRO: `Here are the top-rated restaurants for Chinese cuisine in Agra:`
     - (List of top-rated restaurants)

4. **End the Conversation**:
   - You: `Goodbye`
   - FoodBRO: `Goodbye! Enjoy your meal!`

## Features

- **Restaurant Recommendations**: Get personalized restaurant suggestions based on your preferences.
- **Sentiment Analysis**: Analyze user reviews to determine the sentiment and improve recommendations.
- **Data Visualization**: Visualize restaurant data and user preferences.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
