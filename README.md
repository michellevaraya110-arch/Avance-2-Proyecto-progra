
if opcion == 4:
    print("")
    print("--- Dinero total ---")
    
    total_dinero = 0
    
    
    for i in range(7):
        total_dinero = total_dinero + (ventas_dia[i] * precio_almuerzo)
    
    print("El dinero total de la semana es: ₡", total_dinero)
    print("")

elif opcion == 5:
    print("")
    print("--- Ordenes totales ---")
    
    total_ordenes = 0
    
    
    for i in range(7):
        total_ordenes = total_ordenes + ventas_dia[i]
    
    print("Total de almuerzos vendidos en la semana:", total_ordenes)
    print("")
