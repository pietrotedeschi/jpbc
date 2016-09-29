Forked repository for [jPBC](http://gas.dia.unisa.it/projects/jpbc/).

After [Codehaus termination](http://www.codehaus.org) Maven dependencies didn't work anymore.

Now, you can use the fabulous service [JitPack](https://www.jitpack.io/#pietrotedeschi/jpbc/v2.0.0) to get working again in two simple steps.

**Step 1.** Add the JitPack repository to your build file
```	
<repository>
	<id>jitpack.io</id>
	<url>https://jitpack.io</url>
</repository>
```

**Step 2.** Add the dependency in the form
```
<dependency>
	<groupId>com.github.pietrotedeschi</groupId>
	<artifactId>jpbc</artifactId>
	<version>v2.0.0</version>
</dependency> 
```
Thanks to Emiliano Bonassi!
