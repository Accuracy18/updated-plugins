Installation:
    install the gemini api:
        pip3 install -r requirements.txt or git clone https://github.com/google-gemini/generative-ai-python.git

    link gemini.py to /usr/local/bin to make it a global environmental var:

        ln gemini.py /usr/local/bin/cgemini
        sudo chmod +x /usr/local/bin/cgemini (if nessesary)

Usage:
    mv gemini-plugin dir to <path of micro config dir>/plug/
    open micro
    ctrl-e
    gemini "Hello There"
