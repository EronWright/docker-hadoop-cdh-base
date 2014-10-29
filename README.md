# cdh-base

Cloudera complient container. This image can be used as base to install CDH services, it provide the following environment:

* Centos 6
* jdk1.7.0_65
* Cloudera 5 repositories installed

# Version issue

Cloudera recommands to use a jdk in version 1.7.0_67. This container is build on top of an image which contains a jdk1.7.0_65! The reason is because Oracle website has a bug that does not allow to download rpm directly from a script. This issue will be resolved as soon as possible.

# Oracle license

By using this container, you accept the Oracle Binary Code License Agreement for Java SE available here: http://www.oracle.com/technetwork/java/javase/terms/license/index.html
