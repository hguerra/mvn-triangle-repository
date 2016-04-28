# Maven repository for Triangle

As World Wind Java is not available in public maven repositories you must install it manually via `mvn install` to your local maven repository.
All that belongs to the past.


## Reference

Please check: https://github.com/mpfeil/mvn-repo


## Instructions

First you have to copy the following snippet to you pom.xml of your maven project. If your pom.xml contains a repositories tag
just copy what´s inside.

```
<repositories>
    <repository>
      <id>Triangle Java Repository</id>
      <name>mvn-triangle-repository</name>
      <url>https://github.com/hguerra/mvn-triangle-repository/raw/master/</url>
    </repository>
</repositories>

```

After copying the repository you have to add the following dependencies also to the pom.xml file. Same as above if your pom.xml contains a dependencies tag just copy what´s inside.

```
 <dependencies>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt-natives-linux-amd64</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt-natives-linux-i586</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt-natives-macosx-universal</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt-natives-windows-amd64</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>gluegen-rt-natives-windows-i586</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all-natives-linux-amd64</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all-natives-linux-i586</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all-natives-macosx-universal</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all-natives-windows-amd64</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>jogl-all-natives-windows-i586</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>worldwind</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
    <dependency>
      <groupId>br.inpe.triangle</groupId>
      <artifactId>worldwindx</artifactId>
      <version>1.0</version>
      <scope>compile</scope>
    </dependency>
 </dependencies>

```

Now you´re almost done. Save your pom.xml file and the maven repository is updating.
