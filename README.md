# Driving Data-Driven Innovation: Honda's Journey in the Age of Industry 4.0

## Dataset: - Honda Cars Data. (2023, March 28). Kaggle. https://www.kaggle.com/datasets/omartorres25/honda-data?select=honda_sell_data.csv. 

## The other dataset used for this project is consumer reviews: - Edmunds-Consumer Car Ratings and Reviews. (2018, October 1). Kaggle. https://www.kaggle.com/datasets/ankkur13/edmundsconsumer-car-ratings-and-reviews

## Project Overview:

Cars.com, now the second-largest automotive classified site, holds a vast collection of vehicles for sale. In an effort to assist potential buyers in choosing between economical cars, a web scraper was built to collect up to 5,000 Honda vehicles. Leveraging this dataset, our project aims to drive data-driven innovation in the automotive industry, specifically focusing on Honda cars.

## Tools Used:

- **Tableau:** Built interactive dashboards showcasing daily request counts, hourly distribution, response time, organization breakdown, and HTTP method distribution.
- **Python:**
  - **NLTK Toolkit:** Conducted Natural Language Processing (NLP) and performed sentiment analysis on the consumer reviews.
  - **Pandas, NumPy:** Used for data manipulation and analysis.
  - **Matplotlib, Seaborn:** Utilized for data visualization.
    
## Project Summary:

### 1. Data Collection:

- Built a web scraper to collect up to 5,000 Honda vehicles from cars.com.
- The dataset includes relevant information such as the car's model, condition, price, ratings, drivetrain, and transmission.

### 2. Tableau Dashboard Creation:

- Developed Tableau dashboards showcasing:
  - Daily request counts
  - Hourly distribution
  - Response time
  - Organization breakdown
  - HTTP method distribution
- Implemented filters and dynamic updates for user-driven exploration.

### 3. Sentiment Analysis of Honda Car Reviews:

- Conducted sentiment analysis on consumer reviews of Honda cars.
- **Key Components of Sentiment Analysis:**
  - **Text Data:** Reviews provided by consumers.
  - **Preprocessing:** Removed noise and irrelevant information, including punctuation, special characters, and stopwords.
  - **Feature Extraction:** Converted text into numerical representations using techniques like word embeddings (e.g., Word2Vec or GloVe).
  - **Sentiment Classification:** Categorized reviews into positive and negative sentiments.
- Utilized the NLTK toolkit to tokenize, count words, and calculate sentiment scores.

### 4. Conclusion: Leveraging Sentiment Analysis for Honda Car Reviews:

- Analyzing customer sentiment in reviews of Honda cars, by employing tokenization, word count, and sentiment scoring with the NLTK toolkit in Python, offers valuable insights to both the automotive industry and the manufacturing sector as a whole.
- The process of sentiment analysis begins with breaking down the text in the reviews into tokens, typically individual words. Word count provides a basic but essential metric, indicating the length and complexity of the reviews. However, the real power of sentiment analysis lies in understanding the emotional tone and context conveyed in the text.
- By categorizing reviews into positive and negative sentiments, manufacturers gain the ability to systematically gauge customer satisfaction and identify areas for improvement. Positive reviews can highlight features and aspects of Honda cars that resonate well with customers, while negative reviews pinpoint pain points, defects, or shortcomings.
- This data-driven approach enables manufacturers to make informed decisions about product updates, enhancements, and even future vehicle design. They can prioritize areas that receive positive feedback for further development and address issues raised in negative reviews. For instance, if a significant number of negative reviews mention a recurring problem with a specific car model, the manufacturer can take proactive steps to rectify the issue, improving customer satisfaction and brand loyalty.
- Additionally, sentiment analysis helps the automotive industry understand changing market trends and consumer preferences. This insight can inform marketing strategies, product positioning, and even research and development efforts. It enables manufacturers to stay competitive by adapting to evolving consumer demands and staying ahead of the competition.
- Sentiment analysis, when applied to Honda car reviews and similar consumer feedback, provides a data-driven foundation for enhancing product quality, customer satisfaction, and overall market performance. By embracing the insights offered by sentiment analysis, the manufacturing industry can continue to evolve its products to meet the ever-changing needs and expectations of its customer base, ensuring long-term success and brand loyalty in a highly competitive market.
   
## Repository Contents:

### 1. Tableau Dashboards: 

### Dashboard 1:- https://public.tableau.com/views/ALY6060_group8_Final_Project_Dashboard1/ExteriorRating?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link 

### Dashboard 2:- https://public.tableau.com/views/ALY6060_Group8_Final_Project_Dashboard/Negative?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link 

- Contains Tableau dashboards showcasing daily request counts, hourly distribution, response time, organization breakdown, and HTTP method distribution.

### 2. Python Scripts:

- **Sentiment Analysis:**
  - Conducts sentiment analysis on consumer reviews of Honda cars using the NLTK toolkit.
  - Tokenizes, counts words, and calculates sentiment scores.
- **Data Preprocessing:**
  - Prepares the data for Tableau dashboards and sentiment analysis.
- **Visualization:**
  - Utilizes Matplotlib and Seaborn for data visualization.

### 3. Data:

- Contains the dataset used, which includes relevant information such as the car's model, condition, price, ratings, drivetrain, and transmission.

### 4. Presentation:

- Contains the presentation summarizing the project, including key findings, methodologies, and conclusions drawn.

### 5. Report:

- Contains a detailed report on the sentiment analysis conducted on Honda car reviews, including methodologies, findings, and conclusions.
