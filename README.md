<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spam Email Classification using NLP and Machine Learning</title>
</head>
<body>
    <h1>Spam Email Classification using NLP and Machine Learning</h1>
    <p>This project demonstrates a spam email classification system using Natural Language Processing (NLP) and Machine Learning algorithms. The system classifies emails as either spam or ham (non-spam). This guide provides the steps to set up the environment, install dependencies, and run the application.</p>
    
    <h2>Steps to Set Up the Project</h2>

    <h3>1. Open Anaconda Prompt</h3>
    <p>Launch the <strong>Anaconda Prompt</strong> from the Start Menu.</p>

    <h3>2. Check Available Conda Environments</h3>
    <p>To view all conda environments on your system, run:</p>
    <pre><code>conda env list</code></pre>

    <h3>3. Check the Python Version</h3>
    <p>Verify the Python version installed in the current environment:</p>
    <pre><code>python --version</code></pre>

    <h3>4. Create a New Conda Environment</h3>
    <p>Create a new conda environment with the desired Python version (e.g., Python 3.10):</p>
    <pre><code>conda create --name Spam_Class python=3.10</code></pre>

    <h3>5. Activate the New Environment</h3>
    <p>Activate the newly created environment:</p>
    <pre><code>conda activate Spam_Class</code></pre>

    <h3>6. Install Required Packages</h3>
    <p>Install the necessary libraries for your project:</p>
    <pre><code>pip install pandas</code></pre>
    <pre><code>pip install scikit-learn</code></pre>
    <pre><code>conda install ipykernel</code></pre>
    <pre><code>pip install streamlit</code></pre>

    <h3>7. Open VS Code</h3>
    <p>Launch <strong>Visual Studio Code (VS Code)</strong> to begin working on your project.</p>

    <h3>8. Create a Working Folder</h3>
    <p>Create a folder for your project, for example: <strong>AICTE_SPAM_PRO</strong>.</p>

    <h3>9. Open the Project Folder in VS Code</h3>
    <p>In VS Code, open the folder by navigating to: <code>File &gt; Open Folder &gt; Select the AICTE_SPAM_PRO folder</code></p>

    <h3>10. Create or Open a Jupyter Notebook</h3>
    <p>Create or open the notebook <strong>spam_email_classification.ipynb</strong> in the project folder. Ensure the environment is set to <strong>Spam_Class</strong> in VS Code.</p>

    <h3>11. Train and Save the Model</h3>
    <p>Train the model and save it as <strong>spam.pkl</strong> using the appropriate training scripts in your Jupyter Notebook.</p>

    <h3>12. Run the Streamlit Web Application</h3>
    <p>Create and run the Streamlit app using the file <strong>spamdetector.py</strong>. The app will classify email input as either spam or ham.</p>

    <h3>13. Open Integrated Terminal in VS Code</h3>
    <p>Open the integrated terminal in VS Code to run the application. Ensure the correct environment (<strong>Spam_Class</strong>) is activated.</p>

    <h3>14. Run the Streamlit App</h3>
    <p>Run the Streamlit app using the command:</p>
    <pre><code>streamlit run spamdetector.py</code></pre>

    <h2>Troubleshooting</h2>
    <p>If there are any issues with the environment, ensure you have selected the correct environment (<strong>Spam_Class</strong>) in VS Code.</p>

    <h2>Conclusion</h2>
    <p>By following these steps, you can set up the environment, train the model, and deploy the spam email classifier using Streamlit.</p>
</body>
</html>
