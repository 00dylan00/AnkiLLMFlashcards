# AnkiLLMFlashcards

<div style="text-align: center;">
    <img src="AnkiLLMFlashcards.dalle.webp" alt="ClusterSubmit" width="50%" height="50%">
</div>

AnkiLLMFlashcards is a project that leverages large language models (LLMs) to generate flashcards and decks for Anki, a popular spaced-repetition flashcard program. This repository includes tools and scripts to automate the creation of Anki-compatible flashcard decks from various sources.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)


## Installation

### Prerequisites
- Python 3.7+
- pip

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AnkiLLMFlashcards.git
   cd AnkiLLMFlashcards
   ```
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Ensure you have the necessary models and data:
    * cs-dlp
    * Meta-Llama-3-8B-Instruct
    
## Usage
### Generating Flashcards
To generate flashcards, follow these steps:
1. Prepare your data in the data directory.
2. Run the script to generate flashcards:
```bash
python scripts/generate_flashcards.py
```
### Importing to Anki
After generating the flashcards, import the .apkg files from the generated_decks directory into Anki:

1. Open Anki.
2. Go to File -> Import.
3. Select the .apkg file from generated_decks and click Open.