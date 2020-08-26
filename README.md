# Wrangle-and-analyze
Wrangle-and-analyze Twitter user @dog_rates, known as WeRateDogs.
> Bashayer Alshehri (1 Jul, 2020)


## Intoduction:
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

In this project, I aim to practice Data Wrangling which is an important step in Data Analysis, The Dataset that I used is the tweet archive of Twitter user @dog_rates, known as WeRateDogs.

## The Dataset:
- Enhanced Twitter Archive
> The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which I used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, I have filtered for tweets with ratings only (there are 2356).

- Additional Data via the Twitter API
> we have the WeRateDogs Twitter archive and specifically the tweet IDs within it, can gather this data for all 5000+.So I query Twitter's API to gather this valuable data.

- Image Predictions File
> udacity teachers ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

## Project Details:
We will perform the following tasks in this project:

Data wrangling, which consists of:
- Gathering data
- Assessing data
- Cleaning data
Storing, analyzing, and visualizing our wrangled data.

## Library needed:
- Pandas
- NumPy
- Requests
- Tweepy
- Json
