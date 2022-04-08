# turn_selection_classification
This project is related to the amount of turn arounds that crops should take in a densimetric machine in order to be approved for next processes 

The columns of this projects refers to:
- Orden: Order number
- Preparación: Reciepe code
- Calidad: Quality related to the order number and reciepe
- QQs Netos: Amount of Kilograms of the order
- Línea: Machine Line
- Fecha: Date
- Turno: Shift (Dayshift or Nightshif)
- Analista: Quality Control
- Operador: Operator of the Densimetric Machine
- Hora: Hour
- "% entrada (Trillo)": Input Quality

The next columns should not be used, because they would overfitt the algorithm. Besides, they are Quality Control Samples.
- Def. Prim.: Imperfections in crops samples in first analysis
- Def. Dens.: Imperfections in crops samples in first analysis (second category)
- Def. Otros: Imperfections in crops samples in first analysis (other categories)
- Total Def.: Total imperfections in crops samples 
- % de salida: Quality control in first iteration
- Def. Prim.: Imperfections in crops samples in second analysis
- Def. Dens.: Imperfections in crops samples in second analysis (second category)
- Def. Otros: Imperfections in crops samples in second analysis (other categories)
- Total Def.: Total imperfections in crops samples 
- % de salida: Quality control in second iteration
- Def. Prim.: Imperfections in crops samples in third or more analysis
- Def. Dens.: Imperfections in crops samples in third or more analysis (second category)
- Def. Otros: Imperfections in crops samples in third or more analysis (other categories)
- Total Def.: Total imperfections in crops samples 
- % de salida: Quality control in third or more iteration
- Observaciones
- Prom % de salida: 
- Prom % de Pérdida

##TARGET VALUE##
- Vueltas Ponderadas: Amount of turn arounds that the crops should take on the densimetric machine for an optimal selection (TARGET)


<img width="1921" alt="image" src="https://user-images.githubusercontent.com/69830007/162500874-3e3ea3c8-ed76-45dd-8e0b-74ac29f0712c.png">
