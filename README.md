### Contenidos:

## 1.Hola mundo en python.

---

Comenzamos escribiendo el famoso hello world en py, utilizamos vscode como IDE. Este hello world se realiza con usando el método "print()" que es un método para mostrar algo por consola. Dentro del mismo ingresamos el texto que queremos, en este es el famoso "Hello World".

```python
print("Hello world")
```

## [2](http://2.La). La identacion de python.

Acá comenzamos a aprender sobre la identacion de python, que aunque no lo parezca, es muy importante. Este tema me puso en duda ya que vengo acostumbrado de js donde no hay identacion (aunque siempre use prettier para formatear todo, ya voy a averiguar de algún formateador para python).

```python
if 5 > 3:
    print( '5 es mayor a 3')##funciona por la identacion
print('5 es mayor a 3')## no funciona por la identacion
```

## 3. REPL de python y sus operaciones aritméticas básicas.

El REPL es la consola de python, se puede utilizar yendo a nuestra consola habitual (consola de cmd, powershell, zsh, etc), en la misma ingresando el comando "python3" si es que utilizamos py3 para arriba o "python2" si utilizamos la versión 2. 
Las típicas operaciones aritméticas  son iguales que en todos los lenguajes que ya vi, mostrare un ejemplo a continuación.

```python
## se utiliza python3 para usar la interfaz de py(REPL)
python3 
>>>
## para sumas +
sum = 1 + 2
## para restas -
rest = 2-2
## para multiplicacion *
mult = 2 * 2
## para division /
div = 5/5
## para salir del REPL podemos utilizar exit() o control + z
exit()
```

## 4. Comentarios en python.

Los comentarios en python son faciles de usar, solamente necesitas usar el # en la linea que queremos comentar, obviamente hay que insertarlo al principio de la linea de codigo para comentar todo el resto.

```python
# este es un comentario.
if 3 > 4: #no se cumple. 
    print( '5 es mayor a 3')
if 5 > 3: #se cumple.
    print( '5 es mayor a 3')
```

## 5. Variables en python.

Las variables en python son sin tipo, es decir, podemos asignarles cualquier valor numérico, string, etc sin ningún asignar ningún tipo. Ademas, las variables en python son mutables.

En una parte del código se muestran algunos de los formatos validos para variables

```python
x = 5  # var tipo number
y = 'This is a word'  # var tipo str
print(x, y)  # mostrando x y y

email = 'luca@gmail.com'#var para email
print(email)#mostrando email

#formato valido de variables
myvar = 'pig' #1
my_var = 'pig' #2
_myvar = 'pig' #3
myVar = 'pig' #4
MYVAR = 'pig' #5 usualmente usado para contantes(no se si se usa para variables de entorno como en js)
myVar22 = 'pig'#6
_my_var = 'pig'#7
```

## 6. Múltiples variables en python.

En python nosotros podemos asignar múltiples variables en una misma linea, también podemos copiar múltiples variables en una misma linea de código( aunque lo veo muy poco legible).

```python
a, b, c = 'Lala', 'Lele', 'Lili'
print(a,b,c)
##Muestra: Lala Lele Lili
var1 = var2 = var3 = var4 = 'happy pig'
print(var1,var2,var3,var4)
##Muestra: happy pig happy pig happy pig happy pig
```

## 7. Concatenación.

La concatenación en python es una forma de juntar dos variables para que se muestren juntas, es decir, podemos mostrar como ejemplo dos variables, una que se contenga "Hello", y otra que tenga "World", cuando las concatenemos en un print nos dará "
HelloWorld". Mostrare un ejemplo a continuación. 

```python
inicio = 'Hello'
final = 'World'

print(inicio + final)
##Muestra: HelloWorld
```