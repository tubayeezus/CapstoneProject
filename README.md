# README for Running Jupyter Notebook Code on a Windows 10 Machine

This README provides detailed instructions on how to run the Jupyter Notebook code on a Windows 10 machine, assuming that Python and all required dependencies are not installed. This guide will help you set up a clean environment and execute the code.

## Prerequisites

Before you begin, make sure you have the following software installed on your Windows 10 machine:

1. **Anaconda (Miniconda)**: Anaconda is a Python distribution that includes many data science libraries and tools. You can download Miniconda (a minimal version of Anaconda) from the official website: https://docs.conda.io/en/latest/miniconda.html

## Getting Started

1. **Download the Project Files**:

   - Download the project files, including the Jupyter Notebook and image dataset, from https://github.com/tubayeezus/CapstoneProject.git .

2. **Install Miniconda**:

   - Install Miniconda by following the instructions for your Windows 10 machine from the Miniconda website. During installation, choose to add Miniconda to your system PATH.

3. **Create a New Conda Environment**:

   - Open a command prompt on your Windows 10 machine.
   - Create a new Conda environment by running the following command:
   
     ```
     conda create --name myenv python=3.7
     ```

   Replace `myenv` with the desired environment name and `python=3.7` with your preferred Python version if needed.

4. **Activate the Conda Environment**:

   - Activate the Conda environment by running the following command:

     ```
     conda activate myenv
     ```

   Replace `myenv` with the name of your environment.

5. **Install Required Libraries**:

   - Install the required Python libraries by running the following commands:

     ```
     pip install tensorflow
     pip install matplotlib
     pip install pillow
     pip install opencv-python
     pip install numpy
     pip install pandas
     pip install shap
     pip install scikit-learn
     ```

6. **Navigate to the Project Folder**:

   - Use the `cd` command to navigate to the folder where you downloaded the project files.

7. **Start Jupyter Notebook**:

   - Start Jupyter Notebook by running the following command:

     ```
     jupyter notebook
     ```

   This will open the Jupyter Notebook interface in your web browser.

8. **Open and Run the Notebook**:

   - In the Jupyter Notebook interface, navigate to the folder containing the Jupyter Notebook file (`NEWONE.ipynb`).

   - Click on the notebook file to open it.

   - Follow the instructions within the notebook to run the code cells.

9. **Test the Model with Custom Images**:

   - If you want to test the model with custom images, follow the instructions provided in the notebook. You can upload JPEG images to the specified directory and run the code to make predictions.

##

Enjoy exploring and running the Jupyter Notebook code on your Windows 10 machine!
