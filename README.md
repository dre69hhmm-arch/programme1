# programme1
```python
nom= input("quel est ton nom?")
print("bojour",nom,"!")
age=int(input("tu as quel age?"))
if age>=int(18):
    print("tu as majeur,bienvenue")
    code=int(input("veuillez saisir le mot de passe"))
    print("tu as écrit : ",code)
    while True:
        if code==10101:
              print("bravo accès autorisé")
              break
        else:
            code=int( input("mauvais mot de passe,réssaie une autre fois"))
else:
    print("désolé, tu es encore mineur")
```python     
