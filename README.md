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
