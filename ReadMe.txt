Install Python 3: You can download and install Python 3 from the official Python website: python.org. Follow the installation instructions for your operating system.

Setup:
    a. Open a command prompt or terminal window.
    b. Run the following command to create a virtual environment named venv for your project:
    - For Unix-like systems (Linux, macOS):
    python3 -m venv venv - For Windows:
    python -m venv venv

    c. Activate the virtual environment:
    - For Unix-like systems (Linux, macOS):
    source venv/bin/activate - For Windows PowerShell:
    .\venv\Scripts\Activate.ps1

    d. Check if Python in the virtual environment is active:
    which python If it shows the path to Python inside your project's venv folder, you are ready to proceed to the next step.

    e. Install required packages listed in requirements.txt:
    pip install -r requirements.txt

Testing:

    Run your Python script with the appropriate command:
    - python app.py <filename.pdf>

    For use in WordPress PHP:
    <?php
        // Execute the Python script and capture its output
        $output = shell_exec('python app.py <filename.pdf>');

        // Use $output variable as needed
    ?>
    Replace <filename.pdf> with the actual filename you want to process. Make sure the PDF file is in the same directory or provide the full path to the file.

    With these steps, you should have your Python environment set up correctly and be able to run your app.py script with the desired PDF file.