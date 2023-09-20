# Data Analysis and Processing for Multimodal Dataset

Image Data:

Imbalance Analysis: Checked for class imbalance, plotted a bar plot to visualize the number of images per class, and identified imbalanced classes. Proposed methods to balance the dataset.
Histogram Visualization: Randomly selected 8 images and plotted their respective histograms, labeling each class.
Class Statistics: Calculated and displayed the mean and variance of each class, drawing insights from these statistical measures.
Standardization: Standardized 4 random images from a specific class and visualized the before and after effects, along with observations.
Image Transformations: Applied random rotation, cropping, and scaling transformations to images, showcasing the original and transformed versions.

Audio Data:

Audio Length Analysis: Determined the mean audio length for each class and addressed any class imbalance issues. Proposed methods for dataset balancing.
Spectrogram Visualization: Plotted spectrograms for 4 randomly selected audio recordings from the complete dataset.
Pre-Emphasis Filter: Implemented the Pre-Emphasis filter from scratch, visualized its impact on 4 randomly selected audio recordings, and explained its purpose.
Upsampling and Downsampling: Conducted upsampling and downsampling of audio samples from Class 1, visualized before and after spectrograms, and provided observations.
Audio Format Comparison: Saved a 2-second chunk of a randomly selected audio in .mp3 and .flac formats, then compared spectrograms of all three formats (.wav, .flac, .mp3) and documented observations.

Text Data:

Text Length Analysis: Calculated the average text length for both English and Hindi corpora, including whitespace and punctuation.
Punctuation Removal: Randomly selected 20 parallel texts and removed punctuation and special characters.
Dictionary Creation: Randomly selected 50 parallel texts and created dictionaries for both English and Hindi corpora, ensuring unique numeric mappings for each word.
Top 10 Occurring Words: Identified and plotted the histogram of the top 10 most occurring words in the text data.
