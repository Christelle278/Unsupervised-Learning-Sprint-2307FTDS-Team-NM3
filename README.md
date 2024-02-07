# Unsupervised-Sprint-2307ACDS-Team-EG2

## Future Forge Software

![Logo](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/dfa7ab2f-9068-45f6-9131-66530ff25f0d)

At Future Forge Software, we stand at the forefront of technological evolution, dedicated to shaping the future of software solutions with a specific focus on the entertainment market. As a trailblazing force in the digital landscape, we specialize in harnessing the power of advanced analytics and predictive modeling within the dynamic realm of entertainment.

Our commitment revolves around developing cutting-edge software that empowers businesses in the entertainment industry to foresee opportunities, mitigate risks, and achieve unprecedented success. With a keen focus on the unique challenges and opportunities within the entertainment market, we tailor our solutions to meet the ever-evolving needs of this dynamic sector.

As we aspire to seamlessly integrate predictive analytics into every facet of decision-making in the entertainment industry, our vision is to be the driving force behind a world where foresight transforms content curation, user experiences, and industry standards. Join us on this journey of innovation and discovery as we navigate the digital landscape with a commitment to excellence, innovation, and the transformative potential of predictive analytics. Welcome to Future Forge Software, where the future of entertainment is not just a destination; it's a creation.

## Mission Statement

### Mission:

To harness the power of advanced analytics and predictive modeling, we are committed to developing cutting-edge software solutions that enable businesses to foresee opportunities, mitigate risks, and achieve unprecedented success in an ever-evolving digital landscape.

### Vision:

Aspire to be the driving force behind a world where predictive analytics seamlessly integrates into every facet of decision-making. We envision our software empowering organizations globally, propelling them towards sustained growth, and transforming industries through the foresight of accurate predictions.

### Values:

1. **Innovation:** We thrive on pushing the boundaries of what's possible, constantly exploring new frontiers in predictive technology.

2. **Reliability:** Our software solutions are built on robust frameworks, ensuring reliability and accuracy in every prediction.

3. **Customization:** Recognizing the unique needs of each business, we tailor our solutions to fit seamlessly into your workflow, providing personalized insights.

4. **Collaboration:** We believe in working hand-in-hand with our clients, fostering a collaborative approach that ensures our solutions align perfectly with your objectives

## Our Team:

![Meet the team](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/bdb2aedb-52e9-4499-88c4-ca58e25a249f)

## Problem Statement:

### Project overview:

In the ever-expanding digital landscape of the entertainment industry, the relevance of recommender systems has become pivotal for ensuring individuals receive tailored content recommendations. Future Forge Software, a visionary company in the entertainment domain, aspires to develop a cutting-edge movie recommender system leveraging advanced analytics and predictive modeling. The challenge at hand involves constructing an algorithm, rooted in content or collaborative filtering, capable of accurately predicting user movie ratings for titles they have not yet viewed, based on their historical preferences.

### Project objective:

#### WatchWiz: Your Ultimate Movie Recommender App!
![WatchWiz Logo](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/35937ff0-4832-4179-bf85-0d508d367a7b)


The primary objective is to develop a functional recommender system that excels in predicting user preferences for unseen movies. The system should leverage either content-based filtering or collaborative filtering approach to achieve accurate predictions. By analyzing user historical data, including viewing habits, ratings, and interactions, the recommender system should provide valuable insights into individual preferences, ultimately enhancing user satisfaction and engagement.

## Data:

This dataset consists of several million 5-star ratings obtained from users of the online MovieLens movie recommendation service. The MovieLens dataset has long been used by industry and academic researchers to improve the performance of explicitly-based recommender systems, and now you get to as well!

The data for the MovieLens dataset is maintained by the GroupLens research group in the Department of Computer Science and Engineering at the University of Minnesota. Additional movie content data was legally scraped from IMDB.

- **genome_scores.csv:** a score mapping the strength between movies and tag-related properties. Read more here
- **genome_tags.csv:** user assigned tags for genome-related scores
- **imdb_data.csv:** Additional movie metadata scraped from IMDB using the links.csv file.
- **links.csv:** File providing a mapping between a MovieLens ID and associated IMDB and TMDB IDs.
- **sample_submission.csv:** Sample of the submission format for the hackathon.
- **tags.csv:** User assigned for the movies within the dataset.
- **test.csv:** The test split of the dataset. Contains user and movie IDs with no rating data.
- **train.csv:** The training split of the dataset. Contains user and movie IDs with associated rating data.

### Two-fold approach:

**Content-based model:**

WatchWiz employs content-based filtering by analyzing user-generated tags, genres, and preferences along with movie attributes. This approach involves weighting features, calculating scores, and generating personalized recommendations based on comprehensive user and content profiles. The integration of user-generated tags ensures a more nuanced and engaging recommendation process, enhancing the app's ability to provide tailored content suggestions.
![Content](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/c404befa-44e0-45c4-9fde-06614924bb60)

**Collaborative-based model:**

WatchWiz utilizes collaborative filtering, incorporating both user-based and item-based approaches. By analyzing user behavior and preferences, the app recommends content based on similarities with other users or items that share characteristics with those the user has enjoyed. This dual collaborative filtering strategy enhances the accuracy and diversity of personalized recommendations, providing users with a dynamic and engaging content discovery experience.
![Colab](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/3be6fc56-bcc3-4db9-9c87-25d07926496b)

## Getting Started:

The repository contains the following resources:

- `Unsupervised_Learning_Sprint_2307FTDS_Team_NM3` : The notebook in which the preprocessing and modelling takes place. This is also used to produce files for submission to the Kaggle competition.
- `Required Packages` : Provides a list of libraries that is needed to run the notebook.
- `svd` : The best model sumission in csv form.

## Links:

Kaggle competition: [here](https://www.kaggle.com/competitions/ea-movie-recommendation-predict-2023-2024/overview)

Trello: [here](https://trello.com/b/CgG83gS3/unsupervised-learning-sprint-2307ftds-team-nm3)

Presentation: [here](https://www.canva.com/design/DAF7j-DC0o8/8N0TxE7zjaBFUi3dq2SWRQ/edit?utm_content=DAF7j-DC0o8&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Streamlit app walk-through: [here](https://www.loom.com/share/24e384d8ebba49dfaaf644fcc6d7aa8b)

## Comet:

![Experiments](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/0dcf4c15-9e07-4b7d-b23d-342be262c1aa)

![SVD_pp](https://github.com/Christelle278/Unsupervised-Learning-Sprint-2307FTDS-Team-NM3/assets/142970095/843cb646-b5d3-443a-8d99-34f93d0d332c)
