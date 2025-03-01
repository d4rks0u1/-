# ऋ Share v1
## Overview

This app is designed to enable seamless file sharing over a local network using Wi-Fi or a mobile hotspot. The system eliminates the need for cables, Bluetooth, or cloud uploads, allowing users to transfer files at high speeds directly between devices, from pc to any mobile device which has hotspot.
## Features

- Web Interface: Provides an easy-to-use dashboard for uploading and downloading files.
- Hotspot Enabled: Works without Wi-Fi by turning one device into a hotspot.
- Upload any file type via a simple web interface.
- View uploaded files with timestamps.
- Download files with a single click.
- Fully offline, no external dependencies.
- Built with Flask and local resources.

## Installation

### Prerequisites

- Python 3.x installed
- Flask installed (`pip install flask`)

### Clone the Repository

```sh
git clone https://github.com/yourusername/rshare.git
cd rshare
```

### Run the App

```sh
python app.py
```

The application will run on `http://0.0.0.0:80`.

## File Structure

```
project-root/
│-- app.py  # Main Flask application
│-- templates/
│   │-- index.html  # Homepage
│   │-- send.html  # Upload page
│   │-- files.html  # Files listing page
│   │-- upload/  # Directory where uploaded files are stored
│-- static/
│   │-- filepond.js  # Local file upload script
│   │-- styles.css  # Custom styles
│-- README.md  # User guide
```

## Usage
