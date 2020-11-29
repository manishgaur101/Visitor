# Prime number program
function PrimeNumber(str) { 
var flag = true;
  for(var i=2;i<str;i++)
  {
	  if(flag==true)
	  if(str%i==0)
		{
		  console.log(str+" "+"is not a prime number");
			flag = false;
			}
	}
	if(flag==true)
console.log(str+" is a prime Number");
}

console.log(PrimeNumber(88));