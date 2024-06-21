# Team Profile
## Team ID: C241-PS188
### Our Members
- Yoel Mountanus Sitorus (M004D4KY23) - Machine Learning - Sepuluh Nopember Institute of Technology
- Sony Hermawan (M004D4KY2686) - Machine Learning - Sepuluh Nopember Institute of Technology		
- Anggara Saputra (M004D4KY2537) - Machine Learning - Sepuluh Nopember Institute of Technology		
- Iulyvia Andhani Bayhaqi (C295D4KX0638) - Cloud Computing - Universitas Pembangunan Nasional “Veteran” Jakarta		
- Chattelin (C295D4KX0641) - Cloud Computing - Universitas Pembangunan Nasional “Veteran” Jakarta		
- Liana Eka Wardhani (A009D4KX3750) - Mobile Development - Universitas Gunadarma		
- Muhammad Kemal (A009D4KY4179) - Mobile Development - Universitas Gunadarma		

# Mentalk Machine Learning Project

## **Android**
[Mentalk Android](https://github.com/Bangkit-Capstone-Psychology-Tools/Mentalk-MD)

## **Cloud Computing**
- [Mentalk Cloud Computing](https://github.com/Bangkit-Capstone-Psychology-Tools/m-backend)
- [Mentalk FastAPI](https://gitlab.com/zemetia/mentalk-ml-be)

## **Project Background**
Traditional psychologists face challenges in manually implementing tools for counseling, hindering their effectiveness in addressing the mental health needs of the Indonesian population. To address this issue, our project aims to develop an application that automates existing psychological tools, facilitating both offline and online counseling sessions. The research question guiding our project is how to effectively implement a diverse range of tools within the application. Background information underscores the urgency of the problem, with Indonesia experiencing a high prevalence of mental health disorders, affecting approximately 20% of its population. Dr. Celestinus Eigya Munthe, Director of Prevention and Control of Mental Health and Substance Abuse Problems, highlights the pressing need for scalable solutions to address this issue. The increase of psychological phenomena, worsened by the rise in social media usage, highlights the need for efficient tools to assist psychologists in analysis and diagnosis. Our application seeks to empower psychologists to handle a larger number of clients efficiently, ultimately improving access to mental health services for the Indonesian people. By automating tools and streamlining counseling processes, we aim to provide a robust solution that serves as a pivotal resource in Indonesia's mental health landscape.

# **Machine Learning**

## **Our Colab Link:**
- [Mental Health Predictor](https://colab.research.google.com/drive/1ERyqqPszdFqunyAq0iLuEo25VrEHfSHh?usp=sharing)
- [Depression Level](https://colab.research.google.com/drive/1vk9vF-euRj0f-hoTICzCI9_qb58Gcge-#scrollTo=z2DYgje1nZ9w)
- [Text Emotion](https://colab.research.google.com/drive/1N466i6slbdyNBjfDg_PtZjdPRmIHHmOv#scrollTo=YRN1VM5fga1E)
- [WDYT Yesterday](https://colab.research.google.com/drive/1IVp3cpMxqGC9IO2ZrRMxpvMh_N5BrRAT?authuser=2#scrollTo=gZqdm2mMCDA7)

## **Model Overview**
We use 4 models 2 Natural Language Processing (NLP) and 2 Regression models in our application. These models are designed to automate the process of mental health analysis, making it easier for psychologists to diagnose and treat their patients. The NLP models are used for text analysis, while the Regression models are used for predicting mental health outcomes based on various factors. For more details on each model, please refer to our Colab links.

## **Model Saving and Deployment**

Our models are saved using the `saved_model.pb` format, which allows us to easily store the model's architecture, weights, and training configuration in a single file.

For deployment, we utilize FastAPI, a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. FastAPI is easy to use and deploy, and it's also incredibly efficient at handling requests.

The deployed models are hosted on Cloud Run, a managed compute platform that automatically scales your stateless containers. Cloud Run is developer-friendly, offering seamless integration with existing Google Cloud services.

## **Requirements**

To run the notebook and utilize the model, the following dependencies are required:
- Tensorflow
- Keras
- Matplotlib
- NumPy

## Usage

1. Open one of the colab link above,

2. File > Save a copy in Drive

3. Select Runtime.

4. Run the cells in the notebook to train the model and evaluate its performance.
   
5. Save the trained model as `saved_model.pb` for future use.
   
6. Serve the model using `FastAPI`, refer to our gitlab repo [https://gitlab.com/zemetia/mentalk-ml-be](https://gitlab.com/zemetia/mentalk-ml-be)

7. Use the saved model in your application

## Contributing

Contributions to this project are welcome. If you have any ideas, suggestions, or improvements, please submit a pull request. Make sure to follow the existing coding style and guidelines.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute the code as per the license terms.
