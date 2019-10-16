<html>
<head>
	<title>di1ti</title>
	    <style type="text/css">
		<!--
			.blue{color:#0000FF}
			.purple{color: #FF00FF}
			.宋体{font-family:"宋体"}
		-->
        </style>
</head>
<body>
	<center><h1>A+B Problem</h1></center>
	<div>
	  <h2 data-v-af321868="">题目描述</h2>
	  <div data-v-6156e5d2="" data-v-af321868="">
	    <p>输入两个整数a,b，输出它们的和(|a|,|b|&lt;=10^9)。</p>
	    <p>注意</p>
	    <ol>
	      <li>pascal使用integer会爆掉哦！</li>
	      <li>有负数哦！</li>
	      <li>c/c++的main函数必须是int类型，而且最后要return 0。这不仅对洛谷其他题目有效，而且也是noip/noi比赛的要求！</li>
	    </ol>
	    <p>好吧，同志们，我们就从这一题开始，向着大牛的路进发。</p>
	    <blockquote>
	      <p>任何一个伟大的思想，都有一个微不足道的开始。</p>
	    </blockquote>
	  </div>
	  <h2 data-v-af321868="">输入格式</h2>
	  <div data-v-6156e5d2="" data-v-af321868="">
	    <p>两个整数以空格分开</p>
	  </div>
	  <h2 data-v-af321868="">输出格式</h2>
	  <div data-v-6156e5d2="" data-v-af321868="">
	    <p>一个数</p>
	  </div>
	  <h2 data-v-af321868="">输入输出样例</h2>
	  <div data-v-36768c72="" data-v-af321868="">
	    <div data-v-89a1e792="" data-v-36768c72=""><strong data-v-89a1e792="">输入 #1</strong>
	      <pre data-v-89a1e792="">20 30  </pre>
	    </div>
	    <div data-v-89a1e792="" data-v-36768c72=""><strong data-v-89a1e792="">输出 #1</strong>
	      <pre data-v-89a1e792="">50  </pre>
	    </div>
	  </div>
	  <h2 data-v-af321868="">说明/提示</h2>
	  <div data-v-6156e5d2="" data-v-af321868="">
	    <p>本题各种语言的程序范例：</p>
	    <p>C</p>
	    <pre>
	    #include &lt;stdio.h&gt;    
	    int main() 
	    {      
		int a,b;      
		scanf("%d%d",&amp;a,&amp;b);      
		printf("%d", a+b);      
		return 0;  
	    }  
	    </pre>
	    <hr>
	    <p>C++</p>
	    <pre>
		#include &lt;iostream&gt;  
		#include &lt;cstdio&gt;    
		using namespace std;    
		int main() 
		{      
			int a,b;      
			cin &gt;&gt; a &gt;&gt; b;      
			cout &lt;&lt; a+b;      
			return 0;  
		}  
	    </pre>
	    <hr>
	    <p>Pascal</p>
	    <pre>
	    var a, b: longint;  
	    begin      
		readln(a,b);      
		writeln(a+b);  
	    end.  
	    </pre>
	    <hr>
	    <p>Python2</p>
	    <pre>
	    s=raw_input().split()  
	    print int(s[0]) + int(s[1])  
	    </pre>
	    <hr>
	    <p>Python3</p>
	    <pre>
	    s=input().split()  
	    print(int(s[0]) + int(s[1]))  
	    </pre>
	    <hr>
	    <p>Java</p>
	    <pre>import java.io.*;  
	    import java.util.*;  
	    public class Main 
	    {      
		public static void main(String args[]) 
		throws Exception 
		{          
			Scanner cin=new Scanner(System.in);          
			int a = cin.nextInt(), b = cin.nextInt();          
			System.out.println(a+b);      
		}  
	     }     
	</pre>
	</div><div>题库:<button title="back"><a href="https://zhouningyuan1234.github.io/yyy-Item-bank-resources/"><span class="purple">返回</span></a></button></div>
