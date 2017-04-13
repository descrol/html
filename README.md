# html
<!DOCTYPE  HTML>
<html>
	<head> 
		<meta charset ="utf-8">
		<title></title>
		<script>
		var n1=prompt("請輸入數字","");
		var n2=prompt("請輸入數字","");
		n1=Number(n1);
		n2=Number(n2);
		var op=prompt("請輸入運算 : +, -, *, /","");
		var result;
					
				if(op=="+"){
				result=n1+n2;
				}else if(op=="-"){
				result=n1-n2;
				}else if(op=="*"){
				result=n1*n2;
				}else if(op=="/"){
				result=n1/n2;
				}else
				{
				 result="無效運算子";
				}
			
				alert(result);
					
		</script>
					
	</head>

	</body>
</html> 
