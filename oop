from abc import ABC,abstractclassmethod

class Shapes(ABC):
    @abstractclassmethod
    def area(self):
        print("area")
    @abstractclassmethod
    def perimeter(self):
        print("perimeter")
    def toString(self):pass

class Square(Shapes):
    def __init__(self,edge):
        self.__edge=edge
    def area(self):
        area=self.__edge*self.__edge
        print("area:",area)

    def perimeter(self):
        perimeter=4*self.__edge
        print("perimeter:",perimeter)

    def toString(self):
        print("karenin alanını ve çevresini bulduk...")

class Circle(Shapes):
    PI= 3.14
    def __init__(self,radius):
       self.__radius=radius

    def area(self):
        area=self.PI*self.__radius**2
        print("area:",area)

    def perimeter(self):
        perimeter=2*self.PI*self.__radius
        print("perimeter:",perimeter)

    def toString(self):
        print("dairenin alanını ve çevresini bulduk...")

s2=Square(8)
s2.area()
s2.perimeter()
s2.toString()
s3=Circle(5)
s3.area()
s3.perimeter()
s3.toString()
