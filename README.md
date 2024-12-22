# Practice JavaScript

# prime numbers (  عدد اول بین 1 - 100)
```javascript
for (let i= 1 ; i < 100 ; i++ ) {
    let x=0
    for(let j=2;j<i-1;j++) {
        if(i%j===0) {
        x=1
        }
    }

    if(x===0) {
        console.log(`عدد ${i} اول است `)
    }
    else {
        console.log(`عدد ${i} اول نیست `)
    }
}
```



# even numbers (اعداد زوج بین 1 - 10)
```javascript
for(let i=1 ;i<=10;i++) {
    if(i % 2===0) {
        console.log(i)
    }
}
```

# compare tow numbers (مقایسه بین دو عدد)
```javascript
let num1=10
let num2=20
let result=compare(num1,num2)

console.log(`عدد ${result}  بزرگتر است`)

function compare(number1,number2)
{
    if(number1>number2) {
    return number1
    }
    else {
    return number2
    }
}
```


# sumEvenNumbers (مجموع اعدا زوج بین 1 تا 20)
```javascript
let n=20
let sumEven=n=>{
    let sum=0

    for(let i=0;i<=n;i++) {
        if(i%2===0) {
        sum+=i
        }
    }
    return sum
}
```




# sumNumbersEveninArray (مجموع اعداد  زوج  آرایه )
```
let numbers=[1,12,8,2,31,19]
let result=sumNumbersEveninArray(numbers)
console.log(`مجموع اعداد زوج آرایه  ${result} است `)

function sumNumbersEveninArray(temp) {
    let sum=0
        for (let i=0;i<temp.length;i++)
        {
            if(temp[i]%2===0)
            {
                sum=sum+temp[i]
            }    
        }
    return sum
}
```

# sum Numbers Of Bigger Than 10 with (callback function) (مجموع اعداد بزرگتر از 10 )
```
let numbers=[3,8,16,9,12]
let sum=0
let myFunction=(value)=> {
    if(value>=10)
    {
        sum+=value
    }
}
 
let result= numbers.forEach(myFunction)
 
console.log(sum)
 
```


