tips: ������Ŀ��welcome-file�����Ӽ�Ϊ��������

��ϸ����:http://blog.csdn.net/djy1992/article/details/52335321


1. ����maven web��Ŀ
   * [Eclipseʹ��Maven����web��Ŀ���](http://www.devnote.cn/article/148.html)
   * pom.xml���webapp������
    ```
    <dependency>
    	<groupId>javax.servlet</groupId>
    	<artifactId>javax.servlet-api</artifactId>
    	<version>3.1.0</version>
    	<scope>provided</scope>
    </dependency>
    <dependency>
    	<groupId>javax.servlet</groupId>
    	<artifactId>jsp-api</artifactId>
    	<version>2.0</version>
    	<scope>provided</scope>
    </dependency>
    <dependency>
    	<groupId>javax.servlet</groupId>
    	<artifactId>jstl</artifactId>
    	<version>1.2</version>
    	<scope>provided</scope>
    </dependency>
    ```
   * ����jdk�汾����build->plugins�ڵ�����ӣ�
   ```
    <plugin>
        <groupId>org.apache.maven.plugins</groupId>
        <artifactId>maven-compiler-plugin</artifactId>
        <configuration>
            <source>1.7</source>
            <target>1.7</target>
        </configuration>
    </plugin>
   ```
2. ����spring
3. ����log4j
4. ����dataSource
   * [Spring���ϰ���ͰͿ�Դ����ԴDruid](http://www.html580.com/9880)
   ```
    <!-- druid -->
	<dependency>
		<groupId>com.alibaba</groupId>
		<artifactId>druid</artifactId>
		<version>1.0.7</version>
	</dependency>
   ```
   * [��̷�ʽȡ��Spring�����ĵ�Properties](http://blog.csdn.net/djy1992/article/details/52335321)
   * driverClassName=com.mysql.jdbc.Driver
   * url=jdbc:mysql://localhost:3306/ssm?useUnicode=true&amp;characterEncoding=utf-8
5. ����mybatis
   * [mybatis-spring�ٷ��ĵ� - SqlSessionFactoryBean](http://www.mybatis.org/spring/zh/factorybean.html)
   > �ڴˣ�Ӧ��ɵ��У�
   > 1. �������
   > 2. ɨ��mapper��
6. ����mybatis-generator
   * [MyBatis Generator generatorConfig.xml�������](http://blog.csdn.net/djy1992/article/details/52335321)
   > mybatis-spring�İ汾����1.3.0������ᱨ��
   > java.lang.AbstractMethodError: org.mybatis.spring.transaction.SpringManagedTransaction.getTimeout()L
   * [��Maven�������Mybatis����](http://my.oschina.net/lilw/blog/168304)
7. ��junit����һ��
   * Junit����������test�µ�cn.jxnu.mapper.UserMapperTest
   * [Spring Test+JUnit�������](http://blog.csdn.net/djy1992/article/details/52335321)
8. ����springMVC
   * [spring MVC�������](http://blog.csdn.net/djy1992/article/details/52335321)