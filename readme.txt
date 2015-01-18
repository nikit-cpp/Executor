Add into your pom.xml:

<dependencies>
	<dependency>
		<groupId>com.github.nikit.cpp</groupId>
		<artifactId>Executor</artifactId>
		<version>0.0.3</version>
	</dependency>
	...
</dependencies>

<repositories>
	<repository>
		<id>central</id>
		<url>http://repo1.maven.org/maven2</url>
		<releases>
			<enabled>true</enabled>
		</releases>
		<snapshots>
			<enabled>true</enabled>
		</snapshots>
	</repository>
	<repository>
		<id>my-repo</id>
		<name>my own repo</name>
		<url>http://mvn.16mb.com/repository/</url>
	</repository>
</repositories>
