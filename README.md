# practiceJavaScript

# prime numbers (adade aval)
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
