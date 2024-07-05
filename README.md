TITLE-->RESUME STATISTICS 
PROJECT PURPOSE: 
This project processes resumes from a specified directory, extracts text, and computes statistics like word count and the most frequently occurring word. Results are stored in a pandas DataFrame.
INSTALLATION
Pull Docker Images
NOTE:(Ensure Docker is installed. Then, execute the following commands)
docker pull jupyter/base-notebook
docker pull postgres
docker-compose up
USAGE
-->Access Jupyter Notebook
-->Open your browser and go to http://localhost:8888.
-->Run the getResumeStats function
-->Place all resume files (PDFs or text files) in the input directory.
-->Open the Jupyter Notebook and run the getResumeStats function to process the resumes and generate the DataFrame.

