# Havard_repo
## A Contribution to SOCIAL JUSTICE - The world is far from the ideal of universal equality. Discrimination, hate, and systemic oppression still impact many groups in society. Projects in this track use computer science to help empower these groups.

## A solution using computer science to cater to the problems and empower the social media as a whole.    

# Function 1 (Social Media Scraper)
The main task is to extract the data from WhatsApp,
Instagram, and Twitter to check the real-time data posted on these platforms. This is done by the
“Bot” an automated system that scrapes the posts and messages from these platforms and responds
to the particular user if the content posted by the user is found inappropriate.

# Function 2 (Web Scraper) 
For the fake news analysis a data store has to be maintained, thus two
news reference sites are being scraped for updates of the news and headlines along with the date.
# Function 3 (Fake News Check) 
The data received, in the form of text or image, passes through
the news similarity check algorithm. If that particular news is not appropriate or the result after
applying the cosine similarity algorithm doesn’t exceed a certain threshold point, then the Bot
account sends the URL of the most similar news found in the database on the WhatsApp group or
comments the URL on the post.

# Function 4 (Vulgarity Content Check) 
To check if the image, gif, or video posted or sent by the
user is vulgar, a Convolutional Neural Network has been used. If the image is found to be vulgar,
then the particular user is asked to delete the content from the Bot account.

# Function 5 (Toxic/ Abusive Text Check) 
To check if the text in the form of a message or a post
is inappropriate, a toxic text detection algorithm has been used. If the post or the message creates
a negative impact on the society after being posted in mass, the Bot account notifies the particular
user to delete it.

# Function 6 (Web App) 
The main functionality of the web app is to store every news we scrape
in a form of directory and give a better User interface so that, during a random requirement of any
data related to social media it can be accessed on fingertips.
