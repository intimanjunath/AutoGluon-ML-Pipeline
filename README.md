# AutoGluon-ML-Pipeline
AutoGluon is an open-source AutoML framework by AWS that automates the process of building machine learning models. It supports tabular data, NLP, and multimodal learning, offering powerful performance with minimal code.

Key Features:
* Automatic Model Selection: Chooses the best model for your problem automatically.
* Model Ensembles and Stacking: Combines multiple models using ensembling and stacking techniques to boost performance.
* Tabular Data Handling: Excels at working with structured/tabular datasets.
* NLP Support: Offers tools for natural language processing tasks.
* Multimodal Learning: Integrates text, images, and tabular data for more comprehensive learning.

Installation:
To install AutoGluon, use the following command:
->>> pip install autogluon

Example:
With just a few lines of code, you can build, train, and predict using AutoGluon:

->>> from autogluon.tabular import TabularPredictor

->>>predictor = TabularPredictor(label='class').fit('train.csv')

->>>predictions = predictor.predict('test.csv')

AutoGluon makes it possible to create highly effective machine learning models in a matter of minutes!


Assignments:

So here i'll merge few section into part and the colab link will be above. 

**MI-0:**
* A_a Ieee fraud detection: https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/A_a_IEEEfraud_tabular_kaggle.ipynb
* A_b Califonia House Price : https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/A_b_california_house_prediction.ipynb

video -> https://youtu.be/s7PXUxeHgIU 


**MI-1:**

Tabular classification/regression

* B_A_1A tabular-indepth - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_1A_tabular_indepth.ipynb
* B_A_1B tabular quick start - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_1B_Tabular_quick_start.ipynb
* B-A-B Tabular multimodal - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_B_Tabular_multimodal.ipynb
* B-A-C Tabular feature engineering - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_C_tabular_feature_engineering.ipynb
* B-A-D tabular multilabel - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_D_tabular_multilabel.ipynb
* B-A-E tabular GPU - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI%201/B_a_E_tabular_gpu.ipynb

Video -> https://youtu.be/y1G2dEgw554?si=G9WWGqnLiTzUD-4U


**MI-2:**
text classfication
* B_b_A Bigginer text - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI2/B_b_A_beginner_text.ipynb
* B_b_B Multilingual text - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI2/B_b_Bmultilingual_text.ipynb
* B_b_C ner - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI2/B_b_Cner.ipynb

C: text similarity matching/ D: Image classfier 
* CD_A beginner_img_cls - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI2/CD_A_beginner_image_cls.ipynb
* CD_B Clip_zeroshot  - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI2/CD_B_clip_zeroshot.ipynb

Video -> https://youtu.be/tZnxPE1NMuw?si=Of0-ev2wlL7T3Nl_


**MI-3:**
* Cd_C Quick Start COCO  - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI3/CD_C_quick_start_coco.ipynb

E : IMG segmentation  
* E_a Beginner semantic seg - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI3/E_a_beginner_semantic_seg.ipynb
* E_b document_classification - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI3/E_b_document_classification.ipynb
* E_c PDF clasification - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI3/E_c_pdf_classification.ipynb

video -> https://youtu.be/9kinHzEnQOk?si=e0KbAiow8pYN0YJu


**MI-4:**
F: Semantic matching 
* F_A Image to image  - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI4/F_A_Image_to_Image.ipynb
* F_B Text2text - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI4/F_B_text2text_matching.ipynb
* F_C image_texr matching - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI4/F_C_image_text_matching.ipynb
* F_D zero_shot_img_text - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI4/F_D_zero_shot_img_txt_matching.ipynb
* F_E text_semantic_Search - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI4/F_E_text_semantic_search.ipynb

Video -> https://youtu.be/nS8C4MQ58zQ?si=sY6SOrp526NL_BGZ


**MI-5:**
G : MultiModal mixed 
* G_A multimodal_text_tabular - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/G_A_multimodal_text_tabular.ipynb
* G_B beginner_multimodal - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/G_B_beginner_multimodal.ipynb
* G_C multimodal_ner - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/G_C_multimodal_ner.ipynb

H : Time series 
* H_A forecasting indepth - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/H_A_forecasting_indepth.ipynb
* H_B forecaseting chronos - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/H_B_forecasting_chronos.ipynb
* object detection colab of autogluin - https://github.com/intimanjunath/AutoGluon-ML-Pipeline/blob/master/MI5/G_B_beginner_multimodal.ipynb

video -> https://youtu.be/gENkKOLjncA?si=Pc-VvmFIUgy1Y6Tl 

