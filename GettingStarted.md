# Getting Started #



# 1. Create Template Project #

At first create a template project (ex.
[MyTemplate](http://templateit.googlecode.com/svn/trunk/MyTemplate/)).

Use 'com.example' as package name (namespace)
for folder names and source code.

Project name and package name in text file or folder
will be replaced during unpacking.

![http://templateit.googlecode.com/svn/assets/tmpl1.png](http://templateit.googlecode.com/svn/assets/tmpl1.png)

![http://templateit.googlecode.com/svn/assets/tmpl2.png](http://templateit.googlecode.com/svn/assets/tmpl2.png)

![http://templateit.googlecode.com/svn/assets/tmpl3.png](http://templateit.googlecode.com/svn/assets/tmpl3.png)

# 2. Setup templateit #

Download templateit from
[here](http://code.google.com/p/templateit/downloads/list).

Create folder 'templateit' under project folder and
copy build.xml, config.xml, templateit.jar into.

![http://templateit.googlecode.com/svn/assets/deploy1.png](http://templateit.googlecode.com/svn/assets/deploy1.png)

# 3. Create Package #

Open context menu and run build.xml.

![http://templateit.googlecode.com/svn/assets/run1.png](http://templateit.googlecode.com/svn/assets/run1.png)

After running, select folder 'templateit' and enter
F5 key to refresh then you can see folder 'dist'
where a package created in.

![http://templateit.googlecode.com/svn/assets/run2.png](http://templateit.googlecode.com/svn/assets/run2.png)

# 4. Test Your Package #

Unpack your package from command line.
```
java -jar <Your Package> <Package Name> <Project Name>
```
```
java -jar MyTemplate.v201301010000.jar a.b.c MyTarget
```
![http://templateit.googlecode.com/svn/assets/test1.png](http://templateit.googlecode.com/svn/assets/test1.png)

Check unpacking result.

![http://templateit.googlecode.com/svn/assets/tgt1.png](http://templateit.googlecode.com/svn/assets/tgt1.png)

![http://templateit.googlecode.com/svn/assets/tgt2.png](http://templateit.googlecode.com/svn/assets/tgt2.png)

![http://templateit.googlecode.com/svn/assets/tgt3.png](http://templateit.googlecode.com/svn/assets/tgt3.png)