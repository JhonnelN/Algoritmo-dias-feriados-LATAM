# Algoritmo dias feriados

Este proyecto esta realizado con la intencion de calcular los dias feriados en latinoamerica

## USO
Para usar esta libreria se debe instanciar la clase FeriadosLatam, y cada metodo devuelve una lista con los feriados en un formato de tupla (mes,dia)

```python
feriados = FeriadosLatam()
print("Feriados en México:", feriados.mexico())
print("Feriados en Colombia:", feriados.colombia())
print("Feriados en El Salvador:", feriados.salvador())
print("Feriados en Honduras:", feriados.honduras())
print("Feriados en Nicaragua:", feriados.nicaragua())
print("Feriados en Venezuela:", feriados.venezuela())
```
