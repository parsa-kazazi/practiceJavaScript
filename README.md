# practiceJavaScript

# prime numbers (  عدد اول بین 1 - 100)
for (let i= 1 ; i < 100 ; i++ )

{

let x=0

for(let j=2;j<i-1;j++)

{

if(i%j===0)

{x=1}

}

if(x===0)

{console.log(`عدد ${i} اول است `)}

else

{console.log(`عدد ${i} اول نیست `)}

}




# even numbers (اعداد زوج بین 1 - 10)
for(let i=1 ;i<=10;i++){

if(i % 2===0)

{console.log(i)}

}

