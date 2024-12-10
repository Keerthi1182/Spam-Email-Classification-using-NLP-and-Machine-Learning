<h1>Spam Email Classification using NLP and Machine Learning</h1>
<p>This project demonstrates a spam email classification system using Natural Language Processing (NLP) and Machine Learning algorithms. The system classifies emails as either spam or ham (non-spam). This guide provides the steps to set up the environment, install dependencies, and run the application.</p>
<h2>Steps to Set Up the Project</h2>
<h3>1. Open Anaconda Prompt</h3>
<p>Launch the Anaconda Prompt from the Start Menu.</p>

<h3>2. Check Available Conda Environments</h3>
<p>To view all conda environments on your system, run:</p>
<p><code>conda env list</code></p>

<h3>3. Check the Python Version</h3>
<p>Verify the Python version installed in the current environment:</p>
<p><code>python --version</code></p>

<h3>4. Create a New Conda Environment</h3>
<p>Create a new conda environment with the desired Python version (e.g., Python 3.10):</p>
<p><code>conda create --name Spam_Class python=3.10</code></p>

<h3>5. Activate the New Environment</h3>
<p>Activate the newly created environment:</p>
<p><code>conda activate Spam_Class</code></p>

<h3>6. Install Required Packages</h3>
<p>Install the necessary libraries for your project:</p>
<p><code>pip install pandas</code></p>
<p><code>pip install scikit-learn</code></p>
<p><code>conda install ipykernel</code></p>
<p><code>pip install streamlit</code></p>

<h3>7. Open VS Code</h3>
<p>Launch Visual Studio Code (VS Code) to begin working on your project.</p>

<h3>8. Create a Working Folder</h3>
<p>Create a folder for your project, for example: AICTE_SPAM_PRO.</p>

<h3>9. Open the Project Folder in VS Code</h3>
<p>In VS Code, open the folder by navigating to:</p>
<p><code>File &gt; Open Folder &gt; Select the AICTE_SPAM_PRO folder</code></p>

<h3>10. Create or Open a Jupyter Notebook</h3>
<p>Create or open the notebook <code>Spam Detector.ipynb</code> in the project folder. Ensure the environment is set to <code>Spam_Class</code> in VS Code.</p>

<h3>11. Train and Save the Model</h3>
<p>Train the models and save it as spam123.pkl and vec123.pkl using the appropriate training scripts in your Jupyter Notebook.</p>

<h3>12. Run the Streamlit Web Application</h3>
<p>Create and run the Streamlit app using the file <code>spamdetector.py</code>. The app will classify email input as either spam or ham.</p>

<h3>13. Open Integrated Terminal in VS Code</h3>
<p>Open the integrated terminal in VS Code to run the application. Ensure the correct environment (<code>Spam_Class</code>) is activated.</p>

<h3>14. Run the Streamlit App</h3>
<p>Run the Streamlit app using the command:</p>
<p><code>streamlit run spamdetector.py</code></p>

<h3>Troubleshooting</h3>
<p>If there are any issues with the environment, ensure you have selected the correct environment (<code>Spam_Class</code>) in VS Code.</p>

<h3>Conclusion</h3>
<p>By following these steps, you can set up the environment, train the model, and deploy the spam email classifier using Streamlit.</p>

<h3>File Names Used:</h3>
<ul>
  <li><code>Spam Detector.ipynb</code>: Jupyter notebook used for training and testing the model.</li>
  <li><code>spam123.pkl</code>: The saved trained model file.</li>
  <li><code>vec123.pkl.pkl</code>: The saved trained model file.</li>
  <li><code>spamdetector.py</code>: Python script for deploying the Streamlit web application.</li>
</ul>
