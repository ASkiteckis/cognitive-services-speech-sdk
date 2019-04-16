# How to use the Speech Services Batch Transcription API from Python

To execute the sample you need to generate the Python client library.

To do this follow these steps:

1. Go to https://editor.swagger.io
2. Click **File**, then click **Import URL**
3. Enter the Swagger URL including the region for your Speech Services subscription: `https://<your-region>.cris.ai/docs/v2.0/swagger`
4. Click **Generate Client** and select **Python**
5. Save the client library
6. Extract the downloaded python-client-generated.zip somewhere in your file system.
7. Install the extracted python-client module in your Python environment using pip: `pip install path/to/package/python-client`.
8. The installed package has the name `swagger_client`. You can check that the installation worked using the command `python -c "import swagger_client"`.


The sample code itself is [main.py](python-client/main.py). You can use a development environment like PyCharm to edit, debug, and execute the sample.
