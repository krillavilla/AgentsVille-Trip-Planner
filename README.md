# AgentsVille Trip Planner

## Overview
AgentsVille Trip Planner is an AI-powered system that helps plan personalized vacations to the fictional city of AgentsVille. The system uses advanced LLM reasoning techniques to create detailed itineraries based on user preferences, weather conditions, and available activities.

## Features
- **Personalized Itineraries**: Creates travel plans based on travelers' interests and preferences
- **Weather-Aware Planning**: Avoids scheduling outdoor activities during inclement weather
- **Budget Management**: Ensures the total cost stays within the specified budget
- **Activity Recommendations**: Suggests activities that match travelers' interests
- **Itinerary Revision**: Refines the initial plan based on feedback and evaluation

## Project Structure
- `project_starter.ipynb`: Main Jupyter notebook containing the implementation
- `project_lib.py`: Helper functions, Pydantic models, and mock API calls
- `.env`: Stores the OpenAI API key (you need to add your own key)
- `README.md`: Project documentation

## LLM Reasoning Techniques
The project demonstrates several advanced LLM reasoning techniques:
1. **Role-Based Prompting**: Agents act as specialized travel planners
2. **Chain-of-Thought Reasoning**: Step-by-step planning of itineraries
3. **ReAct Prompting**: Thought → Action → Observation cycles
4. **Feedback Loops**: Self-evaluation using tools to find mistakes and improve plans

## Setup Instructions
1. Clone the repository:
   ```
   git clone https://github.com/krillavilla/AgentsVille-Trip-Planner.git
   cd AgentsVille-Trip-Planner
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Add your OpenAI API key to the `.env` file:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

4. Open and run the Jupyter notebook:
   ```
   jupyter notebook project_starter.ipynb
   ```

## Usage
The notebook guides you through the process of:
1. Defining vacation details (travelers, dates, interests, budget)
2. Retrieving weather and activity data
3. Generating an initial itinerary
4. Evaluating the itinerary against various criteria
5. Revising the itinerary based on feedback
6. Creating a narrative summary of the trip

## Requirements
- Python 3.8+
- OpenAI API key
- Required packages (see requirements.txt)

## License
This project is for educational purposes only.
