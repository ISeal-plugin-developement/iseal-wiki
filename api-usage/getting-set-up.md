# Getting set up

<details>

<summary>Step 1: Download and set up an IDE</summary>

Download an IDE like [IntelliJ](https://www.jetbrains.com/idea/) (preferred) or [Eclipse](https://www.eclipse.org/downloads/)

</details>

<details>

<summary>Step 2: Create a basic plugin</summary>

A lot of tutorials already exist on this and spigot has a [wiki](https://www.spigotmc.org/wiki/spigot-plugin-development/) on it

Add the dependency to your plugin.yml file:

```yaml
depend: [PowerGems]
```

The repo via jitpack:

```
<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```

And the dependency, remember to replace VERSION with the plugin version:

```
	<dependency>
	    <groupId>com.github.ISeal-plugin-developement</groupId>
	    <artifactId>PowerGems</artifactId>
	    <version>VERSION</version>
	    <scope>provided</scope>
	</dependency>
```

</details>



<details>

<summary>Step 3: Make a new class implementing Gem and let you IDE fill it out</summary>

Let your ide complete the methods and add a constructor with not parameters, with the body invoking super with parameters the gem name (like super("SuperAwesome"); )

You can also @Override the particle() method and return a Particle to have your particle fixed to something

</details>

<details>

<summary>Step 4: Register the gem</summary>

In any class, call

```java
ApiManager.getInstance()
```

to get the instance of the ApiManager, then register the gem with

```java
registerGemClass(Class<? extends Gem> gemClass)
```

You can get the return value that will be true if it was registered successfully

</details>
