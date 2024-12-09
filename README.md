# cadastro-de-clientes-v1.9
# Sistema de cadastro de clientes com registro de id, buscas por id, cpf, cnpj e nome

importações e pips

    import os
    import sys
    from tkinter import *
    from tkinter import END
    from tkinter import ttk, messagebox
    import sqlite3
    from urllib.parse import quote
    from reportlab.pdfgen import canvas
    from reportlab.lib import colors 
    from PIL import Image, ImageTk
    import webbrowser
    import requests
    import re

    
Coloque icone e logo.png  

    Crie o executável

    pyinstaller --onefile --windowed --icon=cadastro.ico --add-data "cadastro.ico;." --add-data "logo.png;." nome-da-aplicacao.py


