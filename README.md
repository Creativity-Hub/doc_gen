
# doc_gen

doc_gen generates a docs.html file with documentation for every class and function description in every .py file in project.

### Format

For standalone functions:

    #Description
    
    def myFunc(arg1, arg2):

For a class:

    #Description
    
    class MyClass:
	    
	    #Description
	    def myOtherFunc():
  
For a class with inherited class:

    #Description
    
    class MyClass(InheritedClass):
    
		#Description
	    def myOtherFunc(arg1=None):

### Usage

Drop doc_gen.py and template.html in your project folder and run 

	python3 doc_gen.py -d 'Docs Title' -g "https://github.com/User/Repo"


### Style

For custom styling edit the `style` tag in template.html, defaults to [Sublime Text ]([https://www.sublimetext.com/](https://www.sublimetext.com/)) Color Scheme


### License
----

MIT