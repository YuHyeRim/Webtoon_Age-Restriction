# A harmless webtoon for all: An automatic age-restriction prediction system for webtoon contents

`Webtoon' a digital version of comics, is one of the leading mainstream cultural contents accessed in South Korea. While the country has allowed a number of webtoon service providers to launch their services in the market, the need to establish new conditions and regulations on webtoon services is crucial for both users and providers. Similar to other cultural formats (e.g., movies), there is a huge amount of demand for content-related restrictions and regulations. Responding to these regulations and the rapidly increasing contents, we aim to propose an automated webtoon content age restriction model using both machine learning and traditional restriction approaches. From a dataset containing webtoon descriptions and thumbnails, we achieved 81.88\% of the F1-score and 79.00\% accuracy in predicting each webtoon's age restrictions. 

# Dataset

We collected Naver Webtoon dataset by crawling the naver webtoon page. 
Check the ipynb file for information on data collection. You may need to modify the code to suit your environment.

# Proposed Method

We performed 3-type classification : text-oriented approach, image-oriented approach, multi-modal approach
![framework](https://user-images.githubusercontent.com/96400041/193738978-adb747dc-0a2b-4aff-8e9d-f6d31d8d8205.png)
