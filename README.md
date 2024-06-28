Sure, here's a `README.md` file for your GitHub repository "Story Finder & Generator":

---

# Story Finder & Generator

## Objective

The primary goal of this project is to generate a story based on a user’s query from the most relevant retrieved description or review. Additionally, the project generates an audio book for the generated story.

## Used Concepts

- Crawling
- Scraping
- Word embedding model: Doc2Vec
- Ranked retrieval using cosine similarity
- Large language model for story generation
- Conversion of text to audio

## Stepwise Approach

### Step 1: Crawl Through Website
- Perform web crawling to gather data from various websites.

### Step 2: Web Scraping
- Extract details such as:
  1. Book ID
  2. Review
  3. Votes

### Step 3: Merge Scraped Data with Review Dataset till 2017
- Integrate the scraped data with an existing review dataset up to the year 2017.

### Step 4: Train Doc2Vec Model
- Train a Doc2Vec model and filter out small reviews.

### Step 5: Convert Reviews to Vectors
- Convert the reviews into vectors using the trained Doc2Vec model.

### Step 6: Find Cosine Similarity
- Calculate cosine similarity between the user query and the review text.

### Step 7: Ranked Retrieval
- Perform ranked retrieval to get the top-5 similar reviews along with all the details.

### Step 8: User Selection
- Ask the user to choose which review or book they want to use for story generation.

### Step 9: Store in Dictionary Format
- Store the selected review or book details in a dictionary format.

### Step 10: Model Details
- **Llama 2**: A collection of pretrained and fine-tuned generative text models ranging from 7 billion to 70 billion parameters.
  - Use a system prompt to instruct the model about the domain of interest and specify the expectations from the model.

### Step 11: Generate Story
- Generate a story from the given description of the book using the large language model.

### Step 12: Convert Story to Audio
- Convert the generated story into an audio file.

## Output

The output of the project includes:
- A generated story based on the user's query.
- An audio book version of the generated story.

---


