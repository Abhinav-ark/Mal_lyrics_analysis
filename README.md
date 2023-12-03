## Malayalam Lyrics Analysis: Unveiling the Soul of Songs

**Team Members**
- Abhinav R
- Rohith M
- Arjun P
- Samya R

**Abstract:**

Our research project, "Malayalam Lyrics Analysis," embarks on an exploration of Malayalam song lyrics, delving into the intricate details that make the art of music and language intersect. In this project, we present a creative and multifaceted approach to the analysis of Malayalam song lyrics.

**Introduction:**

Malayalam music is a vibrant tapestry of culture, emotions, and artistic expressions. Through our project, we aim to unravel the rich tapestry of Malayalam song lyrics, uncovering insights that go beyond the words on paper. We employ a combination of linguistic, literary, and data analysis techniques to unearth the hidden treasures within these songs.

### Methods and ideas used in the project:

1. **Data Loading and Exploration**: The project begins by loading a dataset from a CSV file using the Pandas library. The initial steps include displaying the first 100 rows, generating summary statistics, checking for missing values, and cleaning the data. This ensures that the dataset is well-prepared for analysis.

2. **Data Cleaning and Transformation**:
   - The 'വര്‍ഷം' column is filled with zeros to replace missing values.
   - The 'വര്‍ഷം' column is converted to an integer data type.
   - Unnecessary columns like 'Unnamed: 0', 'അഭിനേതാക്കള്‍', 'രാഗം', and 'വര്‍ഗ്ഗീകരണം' are dropped.
   - Rows with missing values are removed.

3. **Data Analysis**:
   - The number of unique values in the 'വരികൾ' column is counted.
   - Rows with 'വരികൾ' containing the text 'ഇവിടെ ക്ലിക്ക് ചെയ്തു ചേര്‍ക്കാം' are removed.

4. **Repeating Lines Processing**:
   - Lines with a pattern like '[number]' or '(number)' are identified and extracted.
   - The number inside square brackets or parentheses is determined and converted to an integer data type.
   - For each song, lines with the repeating pattern are identified, and the line is duplicated based on the number inside the brackets.
   - The dataset is updated with the modified 'വരികൾ' column.

5. **Analysis Continuation**:
   - The dataset is re-examined to count unique values in the 'വരികൾ' column.
   - The project then appears to repeat the process for another pattern where lines end with '-number'. These lines are identified, and the number is extracted and converted to an integer.

6. **Data Verification and Cleanup**:
   - The project continues to check and clean the data, ensuring the changes are applied consistently.
   - Edge cases are carefully considered and worked upon.


The primary goal of this project appears to be to process and clean the text data in the 'വരികൾ' column, specifically focusing on lines with repeating patterns or variations, and then preparing the dataset for further analysis or research related to Malayalam song lyrics. The methodology involves data cleaning, text pattern recognition, and iterative data transformations to enhance the quality of the dataset for future analysis.

**Conclusion:**

Our "Malayalam Lyrics Analysis" project serves as a unique gateway to the world of Malayalam music and culture. By combining linguistic, literary, and data analysis techniques, we offer a holistic perspective on the lyrical and cultural facets of Malayalam songs. Our findings open up a multitude of avenues for further exploration, demonstrating that lyrics are far more than just words—they are the soul of songs, reflecting the emotions and stories of a community.
