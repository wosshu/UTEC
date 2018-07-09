codigoA = ["A0001", "A0002", "A00032", "A0004", "A0005"]
cantidadA = (100, 50, 200, 60, 70)
valorA = (20, 40, 10, 15, 23)
dicA = {cantidadA[0]:valorA[0],
        cantidadA[1]:valorA[1],
        cantidadA[2]:valorA[2],
        cantidadA[3]:valorA[3],
        cantidadA[4]:valorA[4]}
codigoB = ["B0001", "B0002", "B0003", "B0004", "B0005"]
cantidadB = (150, 400, 250, 200, 20)
valorB = (55, 77, 63, 21, 85)
dicB = {cantidadB[0]:valorB[0],
        cantidadB[1]:valorB[1],
        cantidadB[2]:valorB[2],
        cantidadB[3]:valorB[3],
        cantidadB[4]:valorB[4]}

while dicA!=0:
        cantTOA = cantidadA[0]+cantidadA[1]+cantidadA[2]+cantidadA[3]+cantidadA[4]
        valTOA= (cantidadA[0]*valorA[0])+(cantidadA[1]*valorA[1])+(cantidadA[2]*valorA[2])+(cantidadA[3]*valorA[3])+                                       (cantidadA[4]*valorA[4])
        print(("("+str(cantTOA)+","+str(valTOA)+")"))
        break
while dicB!=0:
        cantTOB = cantidadB[0]+cantidadB[1]+cantidadB[2]+cantidadB[3]+cantidadB[4]
        valTOB= (cantidadB[0]*valorB[0])+(cantidadB[1]*valorB[1])+(cantidadB[2]*valorB[2])+(cantidadB[3]*valorB[3])+                                       (cantidadB[4]*valorB[4])
        print(("("+str(cantTOB)+","+str(valTOB)+")"))
        break
while dicA!=dicB:
        cantTO2 = cantidadA[1]+cantidadB[1]
        valTO2 =(cantidadA[1]*valorA[1])+(cantidadB[1]*valorB[1])
        print(("("+str(cantTO2)+","+str(valTO2)+")"))
        break
