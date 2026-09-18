Integer >> + aNumber 
" Additionner 2 integers" 
^  aNumber additionnerAvecInteger: self 

Integer >> additionnerAvecInteger aNumber 
" Additionner un integer avec un autre objet" 
^ addi(aNumber, self) 

Integer >> additionnerAvecFloat aNumber 
^ addf(aNumber, asFloat(self)) 



Float >> + aNumber
^ aNumber additionnerAvecInteger: self 

Float >> additionnerAvecInteger aNumber
^ addf(self, asFloat(aNumber)) 

Float >> additionnerAvecFloat aNumber
^ addf(self, aNumber) 




