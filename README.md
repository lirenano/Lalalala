# Lalalala
#I want to study the preferences of users on spotify for different music
#@inproceedings{10.1145/3298689.3346977,
author = {Semerci, Oguz and Gruson, Alois and Edwards, Catherinee and Lacker, Ben and Gibson, Clay and Radosavljevic, Vladan},
title = {Homepage Personalization at Spotify},
year = {2019},
isbn = {9781450362436},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3298689.3346977},
doi = {10.1145/3298689.3346977},
abstract = {We aim to surface the best of Spotify for each user on the Home page by providing a personalized space where users can find recommendations of playlists, albums, artists, podcasts tailored to their individual preferences. Hundreds of millions of users listen to music on Spotify each month, with more than 50 million daily active users on the Homepage alone. The quality of the recommendations on Home depends on a multi-armed bandit framework that balances exploration and exploitation and allows us to adapt quickly to changes in user preferences. We employ counterfactual training and reasoning to evaluate new algorithms without having to always rely on A/B testing or randomized data collection experiments [3].In this talk, we explain the methods and technologies used in the end-to-end process of homepage personalization and demonstrate a case study where we show improved user satisfaction over a popularity-based baseline. In addition, we present some of the challenges we faced in implementing such machine learning solutions in a production environment at scale and the approaches used to address them.The first challenge stems from the fact that training and offline evaluation of machine learning methods from incomplete logged feedback data requires robust off-policy estimators that account for several forms of bias [1, 2]. The ability to quickly sanity check and gain confidence in the methods we use in the production system is a crucial foundation for developing and maintaining effective algorithms. We demonstrate how we used a single-feature model, optimized for impression-to-click rate, to validate, and improve if necessary, the methods we use for off-policy estimation and accounting for position bias.Lastly, the business metrics we optimize for do not always reflect the expectations of all users of the Home page at a granular level. Consider a niche, daily podcast producing independent, fact-based news every morning. A small segment of Spotify customers might want to see that content on top of their Home page every morning. We present simple but informative metrics we developed to validate our model's ability to account for such habitual behaviors of our customers.},
booktitle = {Proceedings of the 13th ACM Conference on Recommender Systems},
pages = {527},
numpages = {1},
keywords = {recommender systems, counterfactual reasoning, spotify, personalization, learning-to-rank},
location = {Copenhagen, Denmark},
series = {RecSys '19}
}
#RQ Is spotify's recommendation type for users based on their usual music listening preferences?
#Collect user's listening data, classify similar playlists, and calculate user's listening preferences
