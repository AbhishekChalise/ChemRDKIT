# ChemRDKIT

#  A Drug-Likeness analyzer build using RDKit

 - To be accepted as a drug it should satisfiy the Lipinski rules
 - HBD: Hydrogen Bond Donors : Compound like N-H and O-H are hydrogen bond donors because H is delta positive and N and O are Negative, they pull the electron from the hydrogen slihtly harder and make the Hydrogen delta positive.
 - HBA: Hydrogen Bond Acceptors: Compounds like Oxygen and Nitrogen has lone pairs, Lone pairs are negative and these from a electrostatic attraction with the Hydrogen atom

 O-H ------ :O or O-H -------- : N

 : is lone pair concentrated cloud of negative charge.
 ----- is the electrostatic force.

Molecular Weight: Its molecular weight should be less than 500 

LogP(Lipopilicity/Greasiness): LogP <= 5 (This measures how a drug distributes in water and octanol a type of greasy alcohol used to mimic human body fat
-2 means highly water soluble and hate oil and +3 means it dissolve well in oil so lipinski had a rule <=5 to keep balance in solubility in water and dissolvavibility in oil.
If too fat lovable wont dissolve in water and if too water lover wont dissolve in oil)


Sugar passes every Lipinski rule, yet it's not a medicine. Why? Lipinski is a FILTER, not a judge it only checks if a molecule is SHAPE-compatible with being a pill (size, oiliness, H-bond hands). 
Being a drug ALSO requires BINDING a disease target and treating something. Sugar binds nothing disease-relevant. Filters let it in; function makes it medicine.

Fun Fact, Sugar is so important in the body the proteins take sugar molecule and break it and in that process energy is release which is used by the body, 
another thing proteins use sugar chain to make an id card for itself so that immune system wont attact it.