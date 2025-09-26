#    Creamos el diccionario con los datos.

diccionario = {
    "Nombre": "Stalin Solano",
    "Edad": "38" ,
    "Ciudad": "Montalvo",
    "Profesion": "Soldador" ,
}

#lectura del diccionario
for clave, valor in diccionario.items():
    print(clave, "=", valor)
print("-"*20)

#agregar un nuevo valor

diccionario["Nacionalidad"] = "Ecuatoriano"

#lectura del diccionario
for clave, valor in diccionario.items():
    print(clave, "=", valor)
print("-"*20)

#modificar

diccionario.update({"Ciudad":"Guaranda"})

#lectura del diccionario
for clave, valor in diccionario.items():
    print(clave, "=", valor)
print("-"*20)

#eliminar

diccionario.pop("Edad")
#lectura del diccionario
for clave, valor in diccionario.items():
    print(clave, "=", valor)
print("-"*20)
