# AI Adventure Planner

A Streamlit-based web application that helps users plan their adventures using AI-powered recommendations and tools.

## Features

- 🌍 Smart Destination Suggestions
- 📅 Itinerary Generation
- 💰 Budget Planning
- 🌤️ Weather Integration
- 🎒 Packing List Generator
- 🗣️ Local Insights

## Tech Stack

- Python 3.8+
- Streamlit
- Google Gemini AI API
- Streamlit Components (Option Menu, Lottie)

## Setup

1. Clone the repository:
```bash
git clone <repository-url>
cd ai-adventure-planner
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file and add your Gemini API key:
```
GEMINI_API_KEY=your_api_key_here
```

5. Run the application:
```bash
streamlit run src/app.py
```

## Project Structure

```
ai-adventure-planner/
├── src/
│   ├── app.py           # Main application file
│   ├── pages/           # Page components
│   │   ├── home.py
│   │   ├── planner.py
│   │   └── suggestions.py
│   └── utils/           # Utility functions
├── static/             # Static assets
│   └── images/
├── requirements.txt    # Project dependencies
└── README.md          # Project documentation
```

## Usage

1. Open the application in your web browser
2. Fill out the adventure planning form with your preferences
3. Get AI-generated travel recommendations
4. View, download, or share your adventure plan

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. 