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
ejemplo de respuesta 
```bash
Feriados en México: [(1, 1), (1, 30), (3, 13), (4, 20), (5, 1), (9, 16), (11, 13), (12, 25)]
Feriados en Colombia: [(1, 1), (1, 6), (3, 24), (4, 17), (4, 18), (4, 20), (5, 1), (6, 2), (6, 23), (6, 30), (6, 30), (7, 20), (8, 7), (8, 18), (10, 13), (11, 3), (11, 17), (12, 8), (12, 25)]
Feriados en El Salvador: [(1, 1), (4, 17), (4, 18), (4, 19), (4, 20), (5, 1), (5, 10), (6, 17), (8, 5), (8, 6), (9, 15), (11, 2), (12, 25)]
Feriados en Honduras: [(1, 1), (4, 17), (4, 18), (4, 19), (4, 20), (4, 14), (5, 1), (9, 15), (10, 3), (10, 13), (10, 27), (12, 25)]
Feriados en Nicaragua: [(1, 1), (4, 17), (4, 18), (4, 19), (4, 20), (5, 1), (7, 19), (9, 14), (9, 15), (12, 8), (12, 25)]
Feriados en Venezuela: [(1, 1), (3, 3), (3, 4), (4, 17), (4, 18), (4, 19), (4, 20), (4, 19), (5, 1), (6, 24), (7, 5), (7, 24), (10, 12), (12, 24), (12, 25), (12, 31)]
```