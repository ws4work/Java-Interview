# 算法计算

1.斐波那契数列(简单递归数列)
数列:1,1,2,3,5,8,13...
数列特征:<ol><li>0&lt;n&lt;3:Array[n]=1</li><li>n>=3:Array[n]=(Array[n]-2)+(Array[n]-1)</li></ol>

<pre>
	private static int fibonacci(int n) {
        if(n <= 2)
            return 1;
        else
            return fibonacci(n - 1) + fibonacci(n - 2);
    }
</pre>
