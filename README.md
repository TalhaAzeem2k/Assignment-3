# Assignment-3
GitHub Actions

Step1- Creating a GitHub Repository
git clone https://github.com/TalhaAzeem2k/Assignment-3.git
Cloning into 'Assignment-3'...
warning: You appear to have cloned an empty repository.

C:\Users\hamza\Desktop\Coding>cd Assignment-3


Step2- Creating a Simple Web Application
C:\Users\hamza\Desktop\Coding\Assignment-3>python -m venv venv



Step3-Setting Up GitHub Actions Workflow
C:\Users\hamza\Desktop\Coding\Assignment-3>venv\Scripts\activate



Step4- Installing Libraries
(venv) C:\Users\hamza\Desktop\Coding\Assignment-3>pip install Flask
Collecting Flask
  Downloading flask-2.3.3-py3-none-any.whl (96 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 96.1/96.1 kB 305.6 kB/s eta 0:00:00
Collecting Werkzeug>=2.3.7 (from Flask)
  Downloading werkzeug-2.3.7-py3-none-any.whl (242 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 242.2/242.2 kB 825.5 kB/s eta 0:00:00
Collecting Jinja2>=3.1.2 (from Flask)
  Downloading Jinja2-3.1.2-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.1/133.1 kB 2.7 MB/s eta 0:00:00
Collecting itsdangerous>=2.1.2 (from Flask)
  Downloading itsdangerous-2.1.2-py3-none-any.whl (15 kB)
Collecting click>=8.1.3 (from Flask)
  Downloading click-8.1.7-py3-none-any.whl (97 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 97.9/97.9 kB 1.9 MB/s eta 0:00:00
Collecting blinker>=1.6.2 (from Flask)
  Downloading blinker-1.6.2-py3-none-any.whl (13 kB)
Collecting colorama (from click>=8.1.3->Flask)
  Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Collecting MarkupSafe>=2.0 (from Jinja2>=3.1.2->Flask)
  Downloading MarkupSafe-2.1.3-cp311-cp311-win_amd64.whl (17 kB)
Installing collected packages: MarkupSafe, itsdangerous, colorama, blinker, Werkzeug, Jinja2, click, Flask
Successfully installed Flask-2.3.3 Jinja2-3.1.2 MarkupSafe-2.1.3 Werkzeug-2.3.7 blinker-1.6.2 click-8.1.7 colorama-0.4.6 itsdangerous-2.1.2

[notice] A new release of pip is available: 23.1.2 -> 23.2.1
[notice] To update, run: python.exe -m pip install --upgrade pip


Step5- Giving Input to install python requirements
(venv) C:\Users\hamza\Desktop\Coding\Assignment-3>python.exe -m pip install --upgrade pip
Requirement already satisfied: pip in c:\users\hamza\desktop\coding\assignment-3\venv\lib\site-packages (23.1.2)
Collecting pip
  Downloading pip-23.2.1-py3-none-any.whl (2.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 430.0 kB/s eta 0:00:00
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 23.1.2
    Uninstalling pip-23.1.2:
      Successfully uninstalled pip-23.1.2
Successfully installed pip-23.2.1
