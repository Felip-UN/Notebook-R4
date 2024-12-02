## Reto 4: Notebook de Jupyter
Buenas! bienvenido a mi repo, el notebook se encuentra entre los archivos subidos
El reto 6 parece no mostrarse completo asi que lo comparto aqui (fue el mas complicado)
```python
print("Quieres asignar los valores al centro y radio?")
res=input("y/n: ")
if res=="y":
  print("Ingresa los valores del centro (x, y) y el radio (r) ")
  x = int(input("X : "))
  y = int(input("Y : "))
  r = int(input("Radio mayor que 0: "))
else:
  x, y, r= 0, 0, 5
print("Centro (x,y) Radio (r)")
print(f"x = {x}, y = {y} r = {r}")

print("Ahora escribe las cordenadas de un punto cualquiera")
xv = int(input("X : "))
yv = int(input("Y : "))
d_cuadrada= (xv - x)**2 + (yv - y)**2
if d_cuadrada<r**2:
  print("Tu punto marcado se encuentra dentro del circulo")
elif d_cuadrada==r**2:
  print("Tu punto está sobre el borde del círculo")
else:
  print("Tu punto marcado esta fuera del circulo")
```
