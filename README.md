# second-code-02
codes about method overriding
# program to determine the method overriding  
# Defining a parent class  
class Parent():  
    # producer  
    def __init__(self):  
        self.value = "Inside Parent"  
    # showing a parents method  
    def show(self):  
        print(self.value)         
# Defining a child class  
class Child(Parent):      
    # Constructor  
    def __init__(self):  
        self.value = "Inside Child"       
    # showing the child's method  
    def show(self):  
        print(self.value)  
# Chauffeur's code  
obj1 = Parent()  
obj2 = Child()  
obj1.show()  
obj2.show()  
