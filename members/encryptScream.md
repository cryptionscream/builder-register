# script-money

1. *微信名或昵称： encryptScream
2. *discord的ID： windScream#0588
3. *擅长的建设领域、语言或工具、熟练度：java 使用时长 6年 -熟练  ,python 使用时长 1年 -一般 ,爬虫 使用时长4年-一般 , solidity 使用时长一周-初级.
4. *每周能花在业余项目的时间：* 30小时
5. *区块链建设经验（产品、项目、黑客松、技术文章、代码贡献、艺术创作等）：* 写过一些技术文章，开发过基于Selenium+ZMQ的网页自动化工具。
6. *用任意编程语言计算以下公式*
![](https://latex.codecogs.com/svg.image?\sum_{n=1}^{100}\left&space;(n^{3}-\sqrt[3]{n}&space;\right&space;))
```java
import java.math.BigDecimal;

public class Sigma {
    public static void main(String[] args) {
        double sum = 0;
        for (int i = 1; i <101 ; i++) {
            sum=Math.pow(i,3)-Math.pow(i,(double)1/3)+sum;
        }
        System.out.println(new BigDecimal(sum));

    }
}
```
