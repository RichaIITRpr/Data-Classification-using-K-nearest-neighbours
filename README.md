# Steel Plate Fault Prediction
I have used the Steel Plates Faults Data Set as a csv file (Data.csv). This dataset comes from research by Semeion, Research Center of Sciences of Communication. The original aim of the research was to correctly classify the type of surface defects in stainless steel plates, with six types of possible defects (plus "other"). The Input vector is made up of 27 indicators that approximately describe the geometric shape of the defect and its outline.It consists 1119 tuples each having 27 attributes which are indicators representing the geometric shape of the fault. The last attribute (28th attribute) for every tuple signifies the class label (0 for K_Scratch fault and 1 for Z_Scratch fault). It is a two-class problem.

I used K-nearest neaighbour classifier along with normalization to make the predictions.
