# w3bxAN

w3bxAN is a Python script designed to scan websites for common vulnerabilities, including SQL injection, cross-site scripting (XSS), file inclusion etc. 

## Features

- Scans websites for common vulnerabilities
- Detects SQL injection, XSS, RCE etc.
- Display whether vulnerability is present or NOT.
- Generates Report. 

## Installation

1. Clone the repository: `git clone https://github.com/naqviO7/w3bxAN.git`
2. Install the requirements: `pip install -r requirements.txt`

## Usage

The script takes a single argument, which is the URL of the website you want to scan.<br> 
For example: `python webvulnscan.py https://www.example.com`<br>
<br>Use below command:
- `python w3bxAN.py <url> -t <timeout> -o <path/filename.txt>`

## Results

After the scan is complete, the script will generate a report of its findings, which includes the following information:

- The URL of the page that contains the vulnerability
- The type of vulnerability (e.g. SQL injection, XSS, etc.)
- The recommended course of action to fix the vulnerability
