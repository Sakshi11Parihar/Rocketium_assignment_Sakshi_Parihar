# digital Marketing Analysis

# Introduction

In the world of digital marketing, the success of campaigns depends on various performance metrics. This dataset combines quantitative measures like impressions and engagements with creative details such as headlines, calls-to-action, images, and offers. We're on a journey to explore this dataset, uncovering trends and connections to understand how creative elements impact campaign success. By carefully preparing the data, building models, and evaluating results, our goal is to create a predictive model that can forecast campaign performance. The insights and recommendations from this exploration will be a guide for future digital marketing efforts. This repository provides a detailed investigation, offering a clearer picture of how creative ideas and campaign success go hand in hand.


# Project Pipeline
![Final_Chart](flowchart/Final_Flowchart.png)

## 1. Dataset description

attributes:

'date' : The timestamp when the data was recorded.

'company_name' : The name of the company conducting the digital marketing campaign.

'spend' : The amount of money spent on the campaign.

'impressions' : The number of times the campaign content was displayed.

'likecount' : The count of likes received on the campaign.

'commentcount' : The count of comments received on the campaign.

'repostcount' : The count of times the campaign content was reposted or shared.

'total_engagements' : The overall engagement metric, combining likes, comments, and reposts.

'conversion' : Metric indicating the conversion rate, possibly the percentage of users who took a desired action.

'action_type' : The type of action users took in response to the campaign.

'post_url' : The URL associated with the campaign post.

'post_content' : The textual content or description of the campaign post.

'profile_url' : The URL of the company's profile associated with the campaign.

'video_url' : The URL if the campaign includes a video.

'shared_post_url' : The URL if the campaign post was shared.

'created_at' : The timestamp indicating when the campaign was created.

'size' : The size or dimensions of the campaign content.

'url' : The URL associated with the campaign.

'number_of_faces' : The count of faces detected in the campaign content.

'face_emotion' : The emotional expression detected on faces in the campaign.

'face_position' : The position or location of faces in the campaign content.

'face_area_percentage' : The percentage of the image occupied by faces.

'objects' : Types of objects detected in the campaign content.

'number_of_objects' : The count of objects detected in the campaign.

'primary_object' : The primary object identified in the campaign content.

'primary_object_position' : The position or location of the primary object.

'primary_object_area_percentage' : The percentage of the image occupied by the primary object.

'secondary_object' : The secondary object identified in the campaign content.

'secondary_object_position' : The position or location of the secondary object.

'secondary_object_area_percentage' : The percentage of the image occupied by the secondary object.

'text' : Textual content in the campaign.

'text_length' : The length of the text in characters.

'dominant_colour' : The dominant color in the campaign content.

'cta' : Call-to-action associated with the campaign.

'logos' : Presence or absence of logos in the campaign.

'logo_1_name' : The name of the first logo identified.

'logo_1_position' : The position of the first logo in the campaign.

'logo_1_area_percentage' : The percentage of the image occupied by the first logo.

'logo_2_name' : The name of the second logo identified.

'logo_2_position' : The position of the second logo in the campaign.

'logo_2_area_percentage' : The percentage of the image occupied by the second logo.

'number_of_persons' : The count of persons detected in the campaign content.

'person_area_percentage' : The percentage of the image occupied by persons.

'person_area' : The area occupied by persons in the image.

'style' : The style of the campaign (e.g., Modern, Elegant).

'tone' : The tone of the campaign content (e.g., Informative, Inspirational).

'voice' : The voice or tone used in the campaign (e.g., Friendly, Professional).

'sentiment' : The sentiment associated with the campaign (e.g., Positive, Neutral).

'text_area_percentage' : The percentage of the image occupied by text.

'empty_space_percentage' : The percentage of empty space in the image.

'topic' : The topic or subject matter of the campaign.

'language' : The language used in the campaign.

'#faces', '#persons', '#objects', '#text_length' : Counts representing the number of faces, persons, objects, and the length of text.

## 2. Data Preprocessing  

In the data preprocessing phase, missing values in certain columns have been imputed with the label 'unknown' to maintain the integrity of the dataset. Additionally, columns deemed less relevant, such as links and various URLs (e.g., post URL, profile URL), were dropped to streamline the dataset. Furthermore, to enhance model efficiency and avoid multicollinearity, highly positively correlated columns were identified and removed. The objective was to refine the dataset, focusing on essential features for the subsequent modeling phase while ensuring the integrity of the analysis.
![Data Preparation Chart](flowchart/Data_Preparation.png)


## 3. EDA

## 4. MODEL 
![ML Pipeline_Chart](flowchart/ML_Pipeline.png)


## 5. Result


