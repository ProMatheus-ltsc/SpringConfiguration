复制以下gitee，今天的案例

https://gitee.com/huadahua/spc-ioc-2206.git

JSD2203及之前班级     

Spring认证课程 针对有Spring基础的同学

​	-- 内容多，深度，节奏快 2203  

花倩   联系方式：微信：18612483268

#### IOC

- Spring框架的核心

  ~~~java
  两大核心： ioc   aop
  IOC： 控制反转   inverse of controller
      解读：将对象的创建权交由Spring去管理
      
  以前创建对象：
     T t = new T();  t.xx
     T t1 = new T();
  
  Spring框架中关于对象的管理：
      程序员：定义类，无需自己创建对象，对象均已经由Spring框架帮你创建好了，若要使用，直接从Spring容器获取对象即可。
      
  ~~~

##### 如何将定义的类交由Spring创建

~~~java
Spring中创建的所有对象都叫做Bean对象
~~~

- 显式配置Bean

  ~~~java
  通过@Bean注解完成的，但是@Bean注解必然是作用于配置类中的,@Bean注解是作用于方法上方的
  
  配置类：是Spring框架核心的一个类，通过注解@Configuration来表示
   
  @Configuration
  public class MyConfig{
      @Bean
      public T t(){
          return new T();
      }
      
      @Bean
      public A a(){
          return new A();
      }   
  }
  
  class T{}
  class A{}
  ~~~

  

- 隐式配置Bean



#### 依赖注入



模拟题 --Spring认证考试模拟题





 



