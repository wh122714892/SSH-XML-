# SSH-XML-
Spring，struts2和Hibernate对应的四个XML提醒的文件
1.struts2的配置  windows--》Preference



输入 XML cat



点击xml Catalog 后，



选第一个User Specified Entries ，（先复制Stuts.xml文件中的http://struts.apache.org/dtds/struts-2.3.dtd）然后点Add添加后

复制到key中，key  type选择URI



然后是location添加对应的dtd文件，对用的文件之后给出链接

2.Hibernate的配置前面一致。之后需要配置两个，一个是映射（Mapping文件，一个是configuration文件）。

先说配置Mapping文件，复制对应的xxx.hbm.xml文件中的http://www.hibernate.org/dtd/hibernate-mapping-3.0.dtd到key，同样选择URI，然后选择对用应的location的文件中hibernate-mapping-3.0.dtd文件，

配置configuration文件道理相同，复制对应的hibernate.cfg.xml中的http://www.hibernate.org/dtd/hibernate-configuration-3.0.dtd，选择URI，选择对应的location中的hibernate-configuration-3.0.dtd文件

3.配置spring的道理和前面基本一致，先复制对应的applicationContext.xml中的http://www.springframework.org/schema/beans/spring-beans.xsd到key中，然后keyType选择（Schema location），这一点不一样，之后的location文件选择对应的spring-beans-4.2.xsd文件。

