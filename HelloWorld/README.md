# HelloWorld

## Scala IDE

To familiarize yourself with the Scala IDE, create a small “Hello World” project in Eclipse IDE:

1. Go to “File” - “New” - “Other…” and select “Scala Project” from the folder “Scala Wizards”

2. Chose a project name and select “Finish”  

3. Select “File” - “New” - “Scala Object” to create a new object

4. Enter "Hello" as the name for the object and put "first" as the package name above  

5. Change the source code to the one given below:
  * ```scala
package first
object Hello extends App {
  println("Hello, World!")
}
```

6. Save the file and select “Run” - “Run” from the menu. Chose to run as “Scala Application”  

7. You should see a the hello world output in the Eclipse console.


---------------------------------------------------------

## Creating a Scala Worksheet

Creating a Scala Worksheet is very easy:

1. Right-click on the package "first" in the hello world project that you just created

2. Select “New” - “Scala Worksheet”

3. Choose a name for your worksheet (different than Hello or the name you chose for the “Scala Object” before)

4. Now you can type some Scala code into the worksheet. Every time you save the file, the content of the worksheet will be evaluated. Copy the following code into the object of your worksheet:

```scala
  val x = 1                                       //> x  : Int = 1
  def increase(i: Int) = i + 1                    //> increase: (i: Int)Int
  increase(x)                                     //> res0: Int = 2
```

