# Galaxy Exploration Environment

Explore a simulated universe in this interactive space exploration environment. Built using Python, gym, and Streamlit, this project allows you to control an AI agent as it navigates through a procedurally generated cosmos, encountering planets, resources, and hazards along its journey.

## Features

- **Dynamic Environment**: Utilizes the gym library to create a rich, interactive space exploration environment.
- **AI Agent**: Control an AI agent with simple navigation commands.
- **Procedural Planet Generation**: Experience a universe with uniquely generated planets featuring different characteristics.
- **Streamlit Interface**: A user-friendly web interface for real-time interaction and visualization.
- **Reinforcement Learning**: Incorporates a DQNAgent for potential AI-based decision making.

## Installation

To set up and run this project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://ShaliniAnandaPhD.git
   cd intestellar_galaxy
   ```

2. **Install Dependencies**

   Make sure you have Python installed. Then, install the required packages:

   ```bash
   pip install gym tensorflow matplotlib streamlit numpy 
   ```

3. **Run the Streamlit App**

   ```bash
   streamlit run galaxy9000_env.py
   ```

   This will open the app in your default web browser.

## Usage

Once the Streamlit app is running, you can interact with the environment through the web interface:

- **Show Environment**: Displays the current state of the space environment.
- **Agent Controls**: Use buttons like "Move Forward", "Turn Left", and "Turn Right" to control the AI agent's movements.
- **Generate Random Planet**: Creates a new planet with random features and displays its properties.
- **Explore Temple Event**: Triggers a custom event, showcasing the extendability of the environment.

## Contributing

Contributions to enhance this project are welcome. Please adhere to the following steps for contributing:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

