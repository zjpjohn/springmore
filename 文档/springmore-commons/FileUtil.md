* FileUtil 继承了apache commons FileUtils的所有功能
* 文件复制
```java
File srcDir = new File("srcDir");
File destDir = new File("destDir");
FileUtil.copyDirectory(srcDir, destDir);
```
创建目录
```java
File dir = new File("dir");
FileUtil.forceMkdir(dir);
```
将文件中的内容读出来，并封装到list中
```java
File file = new File("file");
List<String> readLines = FileUtil.readLines(file);
```