
# CharmHealth - Panacea

Panacea is an Intelligent, Compassionate and Organized Patient Dashboard 

Hi, My name is Kalpana and I have built Panacea. In the last 10 years , with my practcical experiences with Doctors and their struggle in adjugding the multitude of information, reports, images etc. I understood that there is a strong need for providing a summarized and meaningful timeline for the patient to provide better insights on patient journey, faster diagnosis and more accurately the prescriptions..

Now how does Panacea work :
Panacea extracts text from all patient reports and scanned images to provide an integrated Clinical and Diagnostic summary. 
Panacea enriches Summary with interactive visual timeline fused with trends of the patients is what makes Panacea Unique..
Panacea has an AI architecture powered by Data Synthesis, Data Analytics and Large Language Models.. It goes through a rigorous cycle of Data Preparation, Cleansing and Invoking Multiple AI models like OpenAI, Google Geminin in getting the patient analytics, Timeline visualization etc.
The final output is an integrated view with 9+ exhautive summaries for the patient including Summary, Patient Sentiment, Tone empathy, Patient emotion, Highlighting Key medicines, Diagnosis, and Timeline analytics

We have taken Theme 2 and 4 (and partly 3) to build Panacea. The themes include Patient Timeline Visualization, Clinical Summary Challenge and Generating Optimal Diagnostics code


Installing Jupyter Notebook
If you haven't installed Jupyter Notebook yet, you can do so using the following steps:

Open a terminal or command prompt.

Install Jupyter using pip (Python's package installer):

bash
Copy code
pip install jupyter
Running Jupyter Notebook
Once Jupyter is installed, you can run it with the following steps:

Open a terminal or command prompt.

Navigate to the directory where you want to create or open your Jupyter Notebook.

Type the following command and press Enter:

bash
Copy code
jupyter notebook
This command will start the Jupyter Notebook server and open your default web browser with the Jupyter Dashboard.

In your web browser, you'll see the Jupyter Dashboard, which displays the files and folders in the current directory.

To create a new notebook, click on the "New" button and select "Python 3" (or another kernel of your choice).

To open an existing notebook, navigate to the notebook file and click on its name.

Using Jupyter Notebook
Once you have a notebook open, you can run individual cells by selecting them and either clicking the "Run" button in the toolbar or pressing Shift + Enter. This allows you to interactively execute code, view outputs, and document your work.

Remember to save your notebook periodically by clicking the "Save" button or pressing Ctrl + S/Cmd + S.

Stopping Jupyter Notebook
To stop the Jupyter Notebook server, go back to the terminal where it's running and press Ctrl + C. It will ask if you want to shut down the server; confirm with y and press Enter.

Additional Tips
Kernel Selection: Make sure the kernel (e.g., Python 3) is selected correctly for your notebook.

Markdown Cells: You can use Markdown cells for documentation. Change the cell type to Markdown in the toolbar.

Code Cells: Write and execute your Python code in code cells.

Help: Jupyter has a lot of features. Explore the menus and toolbar to discover more functionalities.

These instructions should help you get started with running Jupyter Notebooks on your system.

Installing Gradio
If you haven't installed Gradio yet, you can do so using the following steps:

Open a terminal or command prompt.

Install Gradio using pip:

bash
Copy code
pip install gradio
Running a Gradio Application
Once Gradio is installed, you can run a simple Gradio application with the following steps:

Open your preferred Python environment (e.g., Jupyter Notebook, script editor).

Import Gradio:

python
Copy code
import gradio as gr
Define a simple function or model that takes an input and produces an output:

python
Copy code
def my_function(input_text):
    # Your processing logic here
    return "Output: " + input_text
Create a Gradio interface for your function:

python
Copy code
iface = gr.Interface(
    fn=my_function,
    inputs="text",
    outputs="text",
    live=True
)
In this example, inputs and outputs are set to "text," but you can customize them based on your application.

Launch the Gradio interface:

python
Copy code
iface.launch()
This will open a web browser with your Gradio application.

You can interact with the interface, providing input and seeing the corresponding output.

To stop the Gradio application, interrupt the Python script (press Ctrl + C in the terminal or stop execution in your script editor).

Additional Options
Interface Customization: You can customize the appearance and behavior of the Gradio interface by modifying the parameters of the Interface class.

Multiple Inputs/Outputs: Gradio supports multiple inputs and outputs. You can configure them accordingly.

File Uploads: If your application involves file uploads, Gradio supports that as well.

Models Integration: If you're using a machine learning model, you can integrate it into the Gradio interface.

Check the Gradio documentation for more details and advanced features.

These instructions should help you get started with running a basic Gradio application. Customize the code according to your specific use case and requirements.
