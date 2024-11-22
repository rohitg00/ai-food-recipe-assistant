# AI Recipe Assistant

An AI-powered recipe assistant that generates detailed recipes, food images, and provides learning resources.

## Features

- Generate detailed recipes with ingredients and instructions
- AI-generated food images
- Dietary preference support (vegetarian, vegan, gluten-free, keto)
- Multiple cuisine types
- Learning resources and tips
- Modern, responsive UI

## Setup

1. Clone the repository
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```

5. Run the application:
   ```bash
   uvicorn main:app --reload
   ```

6. Open http://localhost:8000 in your browser

## Usage

1. Enter the dish you want to cook
2. (Optional) Select dietary preferences
3. (Optional) Choose cuisine type
4. Click "Get Recipe"
5. View the generated recipe, image, and learning resources

## Requirements

- Python 3.8+
- OpenAI API key
- Modern web browser
