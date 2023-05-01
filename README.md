## **Speak Code**
SpeakCode - Let's create something useful.

## **Do you speak code?**

Developers reuse code as part of maintenance, new development, or upgrades. Automation can be a framework designed to deploy new releases; with minor edits to existing code.  SRE (Software Reliability Engineers) use code to monitor web, application, and database activities. 

Using an existing library of code, developers can develop new functions or features within the application. These changes are made for accessibility or a change in standards or needs of the business.

### **Examples of code that can be recycled or reused**

**Microservices** (A distinctive method of developing software systems that focus on building single-function modules with well-defined interfaces and operations.). 
```java
/* HelloWorld.java
 */

public class HelloWorld
{
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```
**Web APIs** (an application programming interface for either a web server or a web browser) and other web-related components often reuse code.
```json
var xhr = new XMLHttpRequest();
xhr.open("GET", "https://reqres.in/api/products/3", true);
xhr.onload = function(){
    console.log(xhr.responseText);
};
xhr.send();
```
				

**Object-oriented programming (OOP)** organizes software design around data, or objects, rather than functions and logic

**Modular programming**  is a design technique that emphasizes separating the functionality of a program into independent, interchangeable modules, such that each contains everything necessary to execute only one aspect of the desired functionality.

```python
def greet(name):
    """
    This function greets to
    the person passed in as
    a parameter
    """
    print("Hello, " + name + ". Good morning!")
```

```python
def my_func():
	x = 12
	print("Value inside function:",x)

x = 24
my_func()
print("Value outside function:",x)
```
### **Tips for building your code library**

* Choose a consistent method for storing and editing modified code. Github is an excellent example of retaining code ownership, history, and change.

* If using a template, maintain the framework and save copies separately for changes. 

* Research templates and APIs for usability and accessibility.

* Well-documented code and use case.

### **Challenges?**

* Limited knowledge or access to useable code.
* New role or job with limited experience
* Code base changes and a new language is used.

Developers can literally spend hours look through blogs, forums, and support for useable code.

### **AI in Code Development**


The advancement in Artificial Intelligence (AI) can have several benefits in code development, including:

1. Improved efficiency: AI can automate repetitive tasks and assist developers in completing code more quickly, which can increase productivity.

2. Enhanced accuracy: AI can detect errors in code more accurately than humans, reducing the likelihood of bugs and errors in the final product.

3. Better decision making: AI can provide insights into the code development process, helping developers make informed decisions about design choices, algorithm selection, and optimization.

4. Predictive analytics: AI can analyze past code development data to make predictions about future projects, helping developers plan and allocate resources more effectively.

5. Improved code quality: AI can suggest optimizations and improvements to existing code, resulting in higher-quality software.

6. Enhanced testing: AI can help automate and improve testing procedures, which can reduce the time and effort required to test code thoroughly.

Overall, AI can help streamline the code development process and improve the quality of the final product, making it an important tool for developers.

**Speak Code** We are working on a special project that has been in the works for years. With the inclusion of AI we will be able to tell a better story about code. We are working with people that speak the language of code. We are currently working on our features and project list.


