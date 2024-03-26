## Odpowiedzi na polecenia curl w aplikacji Flask oraz ocena kodu przez pylint

Wejście na adres http://127.0.0.1:5000/
   Odpowiedź: Welcome to FlaskBlog
   
Wejście na adres http://127.0.0.1:5000/hello/Paulina
   Odpowiedź: Hello Paulina!

## Ocena kodu przez pylint

************* Module app
app.py:1:0: C0114: Missing module docstring (missing-module-docstring)

app.py:7:0: C0116: Missing function or method docstring (missing-function-docstring)

app.py:12:0: C0116: Missing function or method docstring (missing-function-docstring)

app.py:2:0: W0611: Unused escape imported from markupsafe (unused-import)

-----------------------------------
Your code has been rated at 5.00/10

make: *** [lint] Error 20
