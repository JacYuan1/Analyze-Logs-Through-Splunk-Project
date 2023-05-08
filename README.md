# Analyze Logs Through Splunk

## Table of Contents

- [Introduction](#Introduction)
- [Tools Used](#Tools-Used)
- [Approach to Problem](#Approach-to-Problem)
- [Learning Outcomes](#Learning-Outcomes)
- [References](#References)

<h2 id="#Introduction">Introduction</h2>

The premise of this project is to create logs through a custom database in which the logs will then be forwarded to Splunk for further analysis. The final report will be linked in the [References Section](#References).

<h2 id="#Tools-Used">Tools Used</h2>

The tools used here are the following:

1. [Splunk](https://www.splunk.com/)
2. [Splunk Universal Forwarder](https://www.splunk.com/en_us/download/universal-forwarder.html)
3. [Oracle VM VirtualBox](https://www.virtualbox.org/)
4. Windows 10 ISO
5. [Flask](https://flask.palletsprojects.com/en/2.3.x/)
6. [SQLAlchemy](https://www.sqlalchemy.org/)
7. [Python](https://www.python.org/downloads/)

<h2 id="#Approach-to-Problem">Approach to Problem</h2>

1. Created a web application that will accept user input and store it in the backend DB.
2. Recorded HTTP server and DB logs the application creates by using Flask.
3. Forwarded it to Splunk by using the Splunk Universal Forwarder.
4. Ran a search in Splunk to show the application (web and DB) data forwarded from host pc.

<h2 id="#Learning-Outcomes">Learning Outcomes</h2>

1. Learned how to connect Flask to a database with Flask-SQLAlchemy.
2. Learned how to create simple web application using HyperText Markup Language (HTML).
3. Learned how to log applications using Flask.
4. Learned how to configure, format and test a Flask logger.

## References

[Written report linked here]()
