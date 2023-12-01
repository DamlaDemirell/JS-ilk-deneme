// CONDITIONAL STATEMENTS CODE QUIZ 
/*
Eğer bir şahsın yaşı 18'den küçük ise kafeye giremez. 
Eğer bir şahsın yaşı 18 den büyük ama 23 den küçük ise o zaman kafeye girebilir ama alkol alamaz. 
Eğer şahsın yaşı 23 den büyük ise kafeye girebilir ve alkol alabilir. 
*/



var age;
age= 21 ; 

if (age < 18 ) { 

    console.log ('You can not go to cafe') ; 
} else if (age > 18 && age < 23 ) {
    console.log('You can enter the cafe but you can not drink alcohol') 
} else {
    console.log('you can enter the cafe and  drink alcohol');
}

// TERNARY OPERATOR 
var grade= 60;

grade < 45
? console.log('you can not the exam') 
: console.log('you can the exam')

var result= grade < 45 ? 'failure' : 'success' ; 
console.log(result) ; 



//CODE Quiz 3
/*
Alex, sara, nancy aynı sınıfta okuyorlar.
Alex matematik dersinden , 90,80,95 
Sara 89,76,98 
Nancy 42, 98,83 puan almışlar. Buna göre ; 

1- her birinin ortalama puanlarını hesaplayıp bir değişkende saklayın. 
*/
var gradeAlex = (90 + 80 + 95 ) / 3;
var gradeSara = (89 + 76 + 98 ) / 3; 
var gradeNancy = ( 42 + 98 + 83 ) / 3;

console.log('Alex average grade', gradeAlex) ; 
console.log('Sara average grade' , gradeSara);
console.log('Nancy average grade' , gradeNancy); 

// Hangisinin Ortalamasının daha yüksek olduğunu bulun ve en yüksek alanı konsola saklayın. 
/* ortalamaların aynı cıkabileceğini unutmayın. 
*/

if( gradeAlex > gradeSara && gradeAlex > gradeNancy ) {
    console.log('Alex has the highest grade' , gradeAlex); 
}
else if( gradeSara> gradeAlex && gradeSara> gradeNancy) {
    console.log('Sara has the highest grade' , gradeSara); 
}
else if( gradeNancy > gradeAlex && gradeNancy > gradeSara ) {
    console.log('Nancy has the highest grade' , gradeNancy); 
} else{
console.log('may be there is same average'); 
}


