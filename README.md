# Predictive Analysis for Premium Subscribers

### Project Introduction
Website XYZ, a dynamic music-listening social networking platform, operates under the "freemium" business model. This model offers fundamental services at no cost while providing a range of premium features through a monthly subscription. The project's focus is to predict which individuals would likely transition from free users to premium subscribers within the upcoming 6-month period, specifically in response to a targeted promotional campaign.This project seeks to leverage insights from past campaign data to enhance the understanding of user behavior and guide effective decision-making in ongoing promotional initiatives.

# Dataset 
The analysis draws from a dataset from a prior marketing campaign designed to engage non-subscribers to inform and optimize future promotional strategies.

The dataset encompasses 41,540 records. Within this dataset, 1,540 users are categorized as adopters, while 40,000 are non-adopters. Each record corresponds to a distinct user of the XYZ website who was part of the previous marketing campaign.

The dataset has 25 attributes, each offering valuable user behavior and characteristics insights. The following is a concise breakdown of the attributes, including their name, type, and an explanatory description:
• adopter / binary (0 or 1) / whether a user became a subscriber within the 6 month period after the marketing campaign (target variable)
• user id / integer / unique user id
• age / integer / age in years
• male / integer (0 or 1) / 1 – male, 0 – female
• friend cnt / integer / numbers of friends that the current user has
• avg friend age / real / average age of friends (in years)
• avg friend male / real (between 0 and 1) / percentage of males among friends
• friend country cnt / integer / number of different countries among friends of the current user
• subscriber friend cnt / integer / number of friends who are subscribers of the premium service
• songsListened / integer / total number of tracks this user listened (or reported as listened)
• lovedTracks / integer / total number of different songs that the user “liked”
• posts / integer / number of forum or discussion board posts made by the user
• playlists / integer / number of playlists created by the user
• shouts / integer / number of wall posts received by the user
• good country / integer (0 or 1) / country type of the user: 0 – countries where free usage is more limited, 1 – less limited
• tenure / integer / number of months since the user has registered on the website

# Resolution Procedure
1. 
