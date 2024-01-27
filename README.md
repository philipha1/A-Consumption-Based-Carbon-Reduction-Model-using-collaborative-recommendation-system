This project, which garnered a Top 6 ranking at the CityU FinTech Hackathon, involved an innovative application of data science techniques to promote environmentally conscious consumer choices.

The dataset, sourced from Kaggle, comprised two distinct components: grocery purchase data and carbon emission figures associated with various products.

To quantify the environmental impact of each product, I used the Min-Max Scaler to normalize the carbon emission data, thereby creating a unified metric of 'Carbon Footprint Score'. 

Additionally, I transformed product descriptions into numerical data through word vectorization, assigning each term a corresponding score. 

I was able to generate a  'CFscore' column and integrate that into the grocery dataset, effectively handling consumer behavior with environmental data.

Using the 'Carbon Footprint Score', alongside consumer preferences such as reorder rate and add-to-cart order, I developed a recommendation engine. 

This engine displays a list of the Top 6 recommended products, based on individual user preferences, while simultaneously prioritizing reduced carbon footprint options(Carbon footprint scoring). 

This project not only guides consumers towards more sustainable purchasing decisions
