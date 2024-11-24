# bulksms

A python app using **selenium** to send **sms** messages, **using** the google messages web interface. This is a WIP.

## Project structure

```txt
bulksms/
│
├── main.py                # Entry point: starts the GUI
├── config.py              # Configuration for Selenium
├── requirements.txt       # Project dependencies
├── bulksms/
│   ├── __init__.py        # Package initialization
│   ├── gui.py             # GUI implementation (PyQt)
│   ├── sms_logic.py       # Handles data parsing and validation
│   ├── selenium_driver.py # Selenium browser automation logic
│   └── utils.py           # General-purpose helper functions
│
├── assets/
│   ├── icons/             # Icons for the GUI (optional)
│   └── sample_data.csv    # Sample CSV file for phone numbers
│
└── dist/                  # Output folder for packaged executables
  
```
