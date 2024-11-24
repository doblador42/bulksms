# bulksms
A python app to send sms using the google messages web interface
## Project structure:
```
bulksms/
│
├── main.py                # Entry point: starts the GUI
├── config.py              # Configuration for Selenium (e.g., driver paths, URLs)
├── requirements.txt       # Project dependencies
├── bulksms/
│   ├── __init__.py        # Package initialization
│   ├── gui.py             # GUI implementation (PyQt or Tkinter)
│   ├── sms_logic.py       # Handles data parsing and validation
│   ├── selenium_driver.py # Selenium browser automation logic
│   └── utils.py           # General-purpose helper functions
│
├── assets/
│   ├── icons/             # Icons for the GUI (optional)
│   └── sample_data.xlsx   # Sample Excel file for phone numbers
│
└── dist/                  # Output folder for packaged executables
    └── .keep
```