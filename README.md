
## License
This dataset is shared under the Creative Commons Public Domain Dedication (CC0 1.0). You are free to use, modify, and distribute it for any purpose.
  
## Data Collection Procedure
The dataset was collected on **October 1st, 2024** from TikTok using the [Apify TikTok Hashtag Scraper](https://console.apify.com/actors/f1ZeP0K58iwlqG2pY?addFromActorId=f1ZeP0K58iwlqG2pY) tool (free of charge). Here are the detailed steps for data collection:

- Access the [Apify TikTok Hashtag Scraper](https://console.apify.com/actors/f1ZeP0K58iwlqG2pY?addFromActorId=f1ZeP0K58iwlqG2pY).
- Input the desired hashtags. In this case, the following hashtags were used: #cigarettes, #alcohol, #diet, #workout, #food, #smoking.
- Run the scraper for each hashtag, limiting the number of collected videos to **100 videos per hashtag** to ensure a manageable dataset size.
- After scraping, export the data as a CSV file.
  
I retained the following columns from the scraped data for further analysis:

- **ID**: Unique identifier for each video.
- **createTimeISO**: ISO format date of video creation.
- **commentCount**: Number of comments on the video.
- **diggCount**: Number of likes.
- **playCount**: Number of video views.
- **shareCount**: Number of times the video was shared.
- **text**: Caption associated with the video.
- **webVideoUrl**: URL to view the video on TikTok. 
  
Each row in the dataset corresponds to one TikTok video.

## Data Summary
- Total Instances: 637 videos.
- Sampling Strategy: The data was sampled by limiting the number of videos to 100 per hashtag across six hashtags. 
- Labeling Time Estimate: Based on a preliminary review, labeling each instance in this dataset (categorizing the behavior depicted in the video) is expected to take between 5 to 20 seconds per video. 

