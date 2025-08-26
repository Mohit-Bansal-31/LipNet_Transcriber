# Lipnet Transcriber

This project, named "Lipnet Transcriber", is a **full-stack machine learning application** built using **Python, TensorFlow, and Streamlit**. It leverages a **deep learning lip-reading model** to **transcribe spoken words from video frames**, demonstrating the powerful capabilities of machine learning in a practical application.


## 🚀 Getting Started

To get this project up and running on your local machine:

1.  **Clone the Repository**: All the code, including helper files (`model_util.py` and `utils.py`) and pre-trained model checkpoints, is available on GitHub.
    ```bash
    git clone https://github.com/Mohit-Bansal-31/LipNet_Transcriber
    cd Lipnet_Transcriber 
    ```
2.  **Project Structure**:
    *   Ensure you have a `data` folder at the root, containing an `S1` subdirectory with your `.MPG` video files.
    *   The `lips` virtual environment and pre-trained model checkpoints should also be present.
    *   All application-specific code is primarily located in the `app` folder, including `streamlit_app.py`.
3.  **Run the Streamlit Application**: Navigate into the `app` folder and execute the Streamlit command:
    ```bash
    cd app
    streamlit run streamlit_app.py
    ```
    This will open the application in your web browser.

## 🔭 Potential Extensions

This project offers a robust foundation and can be extended in several ways:

*   **Real-time Webcam Integration**: The current setup could be adapted to replace pre-recorded video feeds with a live webcam input.
*   **Edge Device Deployment**: The model can be deployed on edge devices for more compact and efficient lip-reading solutions.
*   **Further Model Training**: While powerful, the model's accuracy could potentially be enhanced with additional training.