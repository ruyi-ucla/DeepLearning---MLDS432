# Deep Learning: MLDS432 Final Project

Abstract 
-- 
In the era of personalized fashion, leveraging deep learning to recommend outfits based on individual characteristics enhances user experience and inclusivity. This project explores a deep learning-based fashion outfit recommendation system tailored to a user’s skin tone. Utilizing a dataset of fashion images, we employ convolutional neural networks (CNNs) to extract color and texture features, integrating them with skin tone analysis to generate personalized outfit suggestions. The model is trained to identify complementary colors and styles that enhance different skin tones using a combination of image classification, clustering, and recommendation algorithms. Our approach aims to bridge the gap between AI-driven personalization and aesthetic preferences, offering users data-driven fashion guidance. The final system is evaluated based on recommendation accuracy, user satisfaction, and visual appeal, demonstrating the potential of AI in modern fashion styling. 

Beyond recommending outfits based on skin tone, this project can be extended in several directions to enhance personalization and usability. One potential approach is incorporating user input to refine recommendations based on personal preferences, such as preferred color palettes, clothing styles, or specific occasions. By integrating user feedback through a ranking or selection mechanism, the model can continuously improve its suggestions. Another direction is expanding the system to recommend matching products, such as accessories, shoes, or complementary clothing items, creating a cohesive and stylish ensemble. This could be achieved using a multi-modal recommendation system that leverages both image and text-based embeddings.

 Read Data
--
```
import kagglehub
path = kagglehub.dataset_download("paramaggarwal/fashion-product-images-small")
print("Path to dataset files:", path)
```
