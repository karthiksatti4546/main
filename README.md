Website Connectivity Checker

This project is a simple Python program that checks whether a website is online or offline.
It sends a request to the given URL and analyzes the response status to determine connectivity.

How It Works

The program uses the requests library to send an HTTP request to the website.
If the response is successful (status code 200), the site is reachable; otherwise, it is considered down or unreachable.

Requirements

Install the required library:

pip install requests

Usage

Run the script and enter a website URL:

python connectivity_checker.py


Example:

Enter website URL: https://www.google.com
Website is reachable.

Summary

This project helps in quickly checking website availability and understanding basic HTTP connectivity using Python.
