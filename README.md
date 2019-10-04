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
<center><h1 data-v-52820d90=""> P1001 A+B Problem</h1></center>
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
    <pre>import java.io.*;  import java.util.*;  public class Main {      public static void main(String args[]) throws Exception {          Scanner cin=new Scanner(System.in);          int a = cin.nextInt(), b = cin.nextInt();          System.out.println(a+b);      }  }  </pre>
    <hr>
    <p>JavaScript （Node.js）</p>
    <pre>const fs = require('fs')  const data = fs.readFileSync('/dev/stdin')  const result = data.toString('ascii').trim().split(' ').map(x =&gt; parseInt(x)).reduce((a, b) =&gt; a + b, 0)  console.log(result)  process.exit() // 请注意必须在出口点处加入此行  </pre>
    <hr>
    <p>Ruby</p>
    <pre>
    a,b=gets.split.map(&amp;:to_i)  
    print a+b  
    </pre>
    <hr>
    <p>PHP</p>
    <pre>
    &lt;?php  $input = trim(file_get_contents("php://stdin"));  l
    ist($a, $b)=explode(' ', $input);  
    echo $a + $b;  
    </pre>
    <hr>
    <p>Rust</p>
    <pre>use std::io;    fn main(){      let mut input=String::new();      io::stdin().read_line(&amp;mut input).unwrap();      let mut s=input.trim().split(' ');        let a:i32=s.next().unwrap()                 .parse().unwrap();      let b:i32=s.next().unwrap()                 .parse().unwrap();      println!("{}",a+b);  }  </pre>
    <hr>
    <p>Go</p>
    <pre>package main    import "fmt"    func main() {      var a, b int      fmt.Scanf("%d%d", &amp;a, &amp;b)      fmt.Println(a+b)  }  </pre>
    <hr>
    <p>C# Mono</p>
    <pre>using System;    public class APlusB{      private static void Main(){          string[] input = Console.ReadLine().Split(' ');          Console.WriteLine(int.Parse(input[0]) + int.Parse(input[1]));      }  }  </pre>
    <hr>
    <p>Visual Basic Mono</p>
    <pre>Imports System    Module APlusB      Sub Main()          Dim ins As String() = Console.ReadLine().Split(New Char(){" "c})          Console.WriteLine(Int(ins(0))+Int(ins(1)))      End Sub  End Module  </pre>
    <hr>
    <p>Kotlin</p>
    <pre>fun main(args: Array&lt;String&gt;) {      val (a, b) = readLine()!!.split(' ').map(String::toInt)      println(a + b)  }  </pre>
    <hr>
    <p>Haskell</p>
    <pre>main = do      [a, b] &lt;- (map read . words) `fmap` getLine      print (a+b)  </pre>
    <hr>
    <p>Scala</p>
    <pre>object Main extends App {      println(scala.io.StdIn.readLine().split(" ").map(_.toInt).sum)  }  </pre>
    <hr>
    <p>Perl</p>
    <pre>my $in = &lt;STDIN&gt;;  chomp $in;  $in = [split /[\s,]+/, $in];  my $c = $in-&gt;[0] + $in-&gt;[1];  print "$c\n";</pre>
  </div>
</div>

</body>
</html>
