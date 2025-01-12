# Imou API Exploration

This repository contain a python notebook that explores the Imou API. The API is used to interact with Imou devices such as cameras and doorbells. The notebook contains code that demonstrates how to interact with the API to get information about the devices, get snapshots from the cameras, and get video clips from the cameras.

## Installation

This notebook was ran on python version 3.10.11.
To run the notebook, you will need to install the following python packages:
    
```bash
    pip install python-decouple --quiet
    pip install imouapi --quiet
    pip install matplotlib --quiet
    pip install numpy --quiet
    pip install pandas --quiet
    pip install opencv-python --quiet
    pip install pillow --quiet
    
```

## Usage

To use the notebook, you will need to create a `config.json` file in the same directory as the notebook. The `config.json` file should contain the following variables:
    
```json
{
    "IMOU_APP_ID": "your app id",
    "IMOU_APP_SECRET": "your app secret"
}
```

You can get the `IMOU_APP_ID` and `IMOU_APP_SECRET` by creating an account on the Imou website (https://auth.imoulife.com/sign-up?client=open) and creating a new application. The `IMOU_APP_ID` and `IMOU_APP_SECRET` will be provided to you when you create the application.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
