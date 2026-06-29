<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        let num=Number(prompt("enter the number"));
        let rev=0;
        let dup=num;
        while(num!=0)
    {
        let d=Math.floor(num%10);
        rev=rev*10+d;
        num=Math.floor(num/10);

    }
    console.log(dup);
    console.log("the reversed number  "+rev);
     for(let i=1;i<=10;++i)
     {
        console.log(i);
     }
    </script>
</body>
</html># Enterprise-E-Commerce-Platform
