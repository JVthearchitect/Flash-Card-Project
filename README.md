# Language Flash Cards

Learn a new language with this simple flashcard application. Improve your vocabulary by flipping through cards that display words in one language and their translation in another. The app allows you to mark words you've learned and focuses on helping you remember the translations.

## Features

- **Flashcard Display**: View words in one language on the front and their translations on the back of the flashcards.

- **Interactive Learning**: Use buttons to indicate whether you know the translation or not, allowing you to focus on words that require more practice.

- **Persistence**: Your progress is saved, and you can continue learning from where you left off.

## Getting Started

1. Clone the repository or download the script.
2. Ensure you have the necessary dependencies:

    ```bash
    pip install pandas
    ```

3. Run the script:

    ```bash
    python flashcard_app.py
    ```

4. The app will display flashcards, and you can click on the buttons to indicate your knowledge of each word.

## Customization

- **Word Data**: The app reads word data from a CSV file (`data/french_words.csv`). You can customize this file with your own word data.

- **Images**: Images for the flashcard fronts and backs are loaded from the "images" folder. Feel free to replace them with your own images.

## Persistence

The app saves your progress by updating a CSV file (`data/words_to_learn.csv`). Words marked as known are removed from the learning list.

## Dependencies

- pandas: Data manipulation library for Python.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy language learning!
