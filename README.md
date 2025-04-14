🌿 **Medicinal Plants Prediction** 🌱

This project uses a machine learning model to identify Indian medicinal plants from images. It includes a Jupyter notebook and a Streamlit web app for easy use. 📚💻

**Project Overview** 🌟
- **Goal**: Predict the type of medicinal plant from an image. 🖼️
- **Dataset**: Indian Medicinal Leaves Image Dataset from Kaggle. 📊
- **Model**: Trained using TensorFlow/Keras. 🤖
- **Tools**: Python, TensorFlow, Keras, Streamlit, Jupyter Notebook. 🐍

**Files** 📂
- **Medicinal_Plants_prediction.ipynb**: Jupyter notebook with the code to download the dataset, preprocess images, train the model, and test predictions. 📓
- **app.py**: Streamlit web app to upload an image and predict the plant type. 🌐
- **medicinal_leaf_model.h5**: Pre-trained model file (not included in repo due to size; you can generate it by running the notebook). 💾
- **Model_Mobilenet.h5**: Another pre-trained model based on MobileNet (optional). 📈
- **amla.jpg, castor.jpg, bamboo.jpg, aloevera.jpg**: Sample images for testing. 🖼️

**How to Set Up** 🛠️
1. **Clone the Repository**:
   git clone https://github.com/your-username/medicinal-plants-prediction.git
   cd medicinal-plants-prediction 📥

2. **Install Dependencies**:
   Make sure you have Python installed, then install the required libraries:
   pip install -r requirements.txt
   (Create a requirements.txt with these packages: tensorflow, numpy, pandas, matplotlib, streamlit, pillow, kaggle.) 🐍📦

3. **Download the Dataset**:
   - Get a Kaggle API key (kaggle.json) and place it in the project folder. 🔑
   - Run the notebook to download the dataset using:
     !kaggle datasets download -d aryashah2k/indian-medicinal-leaves-dataset
   - Unzip the dataset in the project folder. 📥

4. **Run the Notebook**:
   - Open Medicinal_Plants_prediction.ipynb in Jupyter Notebook or Google Colab. 📓
   - Follow the steps to train the model and test predictions. ✅
   - This will generate medicinal_leaf_model.h5. 💾

5. **Run the Streamlit App**:
   - Start the app with:
     streamlit run app.py
   - Upload an image in the web interface to see the predicted plant type. 🌐🖼️

6. **Optional - Use LocalTunnel**:
   - To share the app online, install Node.js and LocalTunnel:
     npm install -g localtunnel
   - Run Streamlit and LocalTunnel together:
     streamlit run app.py & npx localtunnel --port 8501
   - Use the provided URL to access the app. 🌍🔗

**Usage** 🚀
- **Notebook**: Use it to train the model, test sample images, or explore the dataset. 📓🔍
- **Web App**: Upload any medicinal plant image (jpg, png, jpeg) to get instant predictions. 🌐✅
- **Sample Images**: Test with provided images like amla.jpg or aloevera.jpg. 🖼️

**Notes** 📝
- The dataset is large (around 9GB). Make sure you have enough storage. 💽
- The pre-trained model (medicinal_leaf_model.h5) is not included in the repo. Run the notebook to create it. 💾
- If you face issues with the Kaggle API, check the kaggle.json file permissions (chmod 600 kaggle.json). 🔐
- The Streamlit app requires the dataset folder and model file in the correct paths. 📁

**Requirements** 🛠️
- Python 3.7+ 🐍
- Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Streamlit, Pillow, Kaggle 📚
- Optional: Node.js (for LocalTunnel) 🌐

**Acknowledgments** 🙏
- Dataset: Indian Medicinal Leaves Dataset (https://www.kaggle.com/datasets/aryashah2k/indian-medicinal-leaves-dataset) 📊
- Built with love for learning and plant identification! 💚🌿
