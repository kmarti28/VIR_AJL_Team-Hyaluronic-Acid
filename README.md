# VIR_AJL_Team-Hyaluronic-Acid README

---

### **👥 Team Members**

| Name | GitHub Handle | GitHub Profile Link | Contribution |
| ----- | ----- | ----- | ----- |
|Kennedy Martin| @kmarti28 | https://github.com/kmarti28 | performed data augmentation, fine-tuned CNN model|
|Lucia Njemanze| @lucia175 | https://github.com/lucia175 | built CNN model, finetuned external model|
|Jenny Leana Fotso Ngompe| @LeanaNgompe | https://github.com/LeanaNgompe | performed data augmentation, fine-tune CNN model, refined DenseNet121 Model|
| Alice Gonzalez | @AliceGonzalez1 | | Built DenseNet121 model, performed data augumentation |
| Uchenna Justin | @uchenna-hj | | Dataset Benchmarking |
| Eman Ahmed | @eahmed04 | https://github.com/eahmed04| Dataset Benchmarking |

---

## **🎯 Project Highlights**


* Utilized machine learning techniques with scikit-learn and TensorFlow to develop an inclusive CNN machine learning model for dermatology that accurately classifies skin conditions across all skin tones.
* Achieved an F1 score of 0.4267  and a ranking of 31 on the final Kaggle Leaderboard. 
* Implemented data preprocessing approaches of rotating, shifting, and blurring data images to optimize results within computing constraints.

🔗 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)


---

## **👩🏽‍💻 Setup & Execution** 

**Provide step-by-step instructions so someone else can run your code and reproduce your results. Depending on your setup, include:**

* From Kaggle, copy and edit the starter code
* Review current starter code for understanding
* For the initial run, confirm that all imports complete properly and there are no errors
* The Jupyter notebook cells contain all imports necessary for properly running the code, so as long as they are run in order there should be no issues.

---

## **🏗️ Project Overview**

Break Through Tech has partnered with Algorithmic Justice League and Women in Data Science to create Kaggle challenges. These challenges will allow students to practice machine learning and AI fundamentals. Teams will need to utilize different tools in order to work within Kaggle and then submit their predictions to a leaderboard. 

Equitable AI for Dermatology: This challenge is about making AI better at diagnosing skin conditions for everyone, especially people with darker skin tones. Right now, many dermatology AI tools don’t work as well for these groups because they haven’t been trained on diverse skin images. This can lead to misdiagnoses, delayed treatments, and bigger health disparities.

Our goal is to train a machine-learning model that can accurately classify 21 different skin conditions across all skin tones. Using datasets from Kaggle, our team will work to improve the model’s accuracy.

---

## **📊 Data Exploration**

* The dataset is a subset of the FitzPatrick17k dataset, a labeled collection of about 17,000 images depicting a variety of serious (e.g., melanoma) and cosmetic (e.g., acne) dermatological conditions with a range of skin tones scored on the FitzPatrick skin tone scale (FST).
* We displayed some of the different datasets and attempted to augment them using shifting, blurring, and rotation
* We noticed that there were large disparities in skin condition and skin types
* there was also the skin type that the experts labeled and self-labels that the users gave these disparities made it difficult to decide which of the features were a more accurate depiction of skin condition
* Additionally there were some examples that had no skin condition label (-1) and in that case we were unsure of what to do in those instances.

## **visualizations to include:**

* sample dataset images:
      <img width="425" alt="image" src="https://github.com/user-attachments/assets/4ce9ee73-bf82-476c-8b2b-67f6b4757e43" />
* rotated image:
       ![image](https://github.com/user-attachments/assets/a690e073-2829-4356-b7e4-d59e69b7bfad)
* blurred image:
         ![image](https://github.com/user-attachments/assets/a061c0b2-7b0a-4f81-b569-8a6d75518dff)

---

## **🧠 Model Development**  

**Describe:**

* Models used:
        * CNN -- This model was used initially, however, our team found that there was little improvememnt in scores with increased augmentation and so we pivoted to another approach. 
        * Densenet -- This model is what our team ended with. It enabled us to get a much higher accuracy with the same amount of data augmentation. 
* Initial exploration included finding the counts of each skin type, to determine which skin types were most underrepresented. This aided in knowing where the majority of data augmentation was needed. 

---

## **📈 Results & Key Findings**

**Describe:**

* Our final score ended up being .42677 which landed this team in 31st place on the Kaggle leaderboard. 
* How our model performed overall -- Our second model did much better than the initial CNN. It is our teams belief that if this model had been found sooner we would have been able to increase our accuracy with more data augmentation and data exploration. 

## **🖼️ Impact Narrative**

**AJL challenge:**
   As a team, we used data augmentation to ensure that our training model had equal amounts of all skin tones. We rotated, shifted, and blurred the data so that our training data had a larger range of skin tones. This allows for our model to be trained on more then one skin tone and be able to identify skin conditional regardless of the shade. Below you will see an example of what blurred data looked like:
   ![image](https://github.com/user-attachments/assets/f37f6c7a-447a-441b-8cc8-151c78222c97)

   The broader impact of this model would mean that dermatology AI would be more racially inclusive allowing for all people to use it without fear of misclassification or inaccuracy. Overall, this creates a more inclusive environment for all users.

---

## **🚀 Next Steps & Future Improvements**

* As a team we experienced difficulties in improving the score of our model, we tried to use CNN but it became quickly apparent that CNN might not work.
* With more time our team would have been able to test more models allowing us to have a range of options on how to execute the model.
* We could have looked for more data to have a larger dataset to train and test on.
---

## **📄 References & Additional Resources** 

* Transfer learning and fine-tuning. (n.d.). TensorFlow. https://www.tensorflow.org/tutorials/images/transfer_learning
* Kaggle Tutorial videos
---


















