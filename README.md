# java-console
用户自定义控制台，用于替代系统控制台，用在程序中实时输出打印信息以及捕捉异常信息并输出

使用简介：
public class Test{
    public static void main(String[] args){
   
    MyConsole myConsole = new MyConsole();//创建对象
    myConsole.systemTray();//启动控制台
    
    for(int i = 0;i < 1000;i++){
        int sum = +i;
        System.out.println(sum);//注意使用 println
    }
  }
}


