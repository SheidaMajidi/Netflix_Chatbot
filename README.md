# Netflix_Chatbot
Building a Simple Chatbot for Netflix: A User-Friendly Guide

The code can be divided into three main parts:

## **Netflix Recommendation System**:
- **Techniques and Libraries**:
    - Uses `pandas` for data manipulation and filtering based on user preferences.
    - Visualization with `matplotlib` to display top recommendations in a bar plot.
- This section initiates by prompting users about the types of shows they prefer: either movies or TV shows.
    - **For movies**: Users are given options to further refine their choice based on genres and release years. Based on the user's preferences, the top 10 movie recommendations are then displayed in a bar plot according to IMDb scores.
    - **For TV shows**: The process mirrors the movies, where the user's genre and release year preferences are taken into account to generate top suggestions, displayed as a bar plot based on IMDb scores.

## **How Do I...? Feature**:
- **Techniques and Libraries**:
    - Utilizes conditional statements to guide users through a tree-like structure of queries.
- Aims to guide users on various Netflix functionalities.
    - The user is prompted with a series of options such as searching for titles, accessing subtitles, registering a device, viewing purchased content, managing parental controls, and updating their country.
    - For each option, detailed steps or relevant information is presented to the user based on their selection.

## **Feedback Mechanism**:
- **Techniques and Libraries**:
    - Employs `pandas` for data management and to check user authenticity.
    - Implements basic sentiment analysis using a predefined lexicon to categorize user feedback.
- Users are encouraged to provide feedback about their Netflix experience.
    - The code checks for user authenticity by matching provided user IDs and passwords against a dataset.
    - Once verified, users are asked about their favorite aspects of Netflix and areas they believe need improvement.
    - The user feedback is subjected to sentiment analysis to classify it as positive, negative, or neutral.
    - The results are then stored in feedback dataframes for future use.

**In summary**, this code serves as an interactive tool to assist Netflix users, making use of data manipulation with `pandas`, visualization with `matplotlib`, and basic sentiment analysis techniques to provide recommendations, guidance on platform use, and collect user feedback.
