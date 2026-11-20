#Single Inheritance - 1 parent/base class -> 1 child/derived class
'''class DGT:
    def __init__(self,course):
        self.course = course
    
    def trade(self):
        print("Trade: ",self.course)

class NSTIW_Kolkata(DGT):
    #def __init__(self,duration):
        #self.duration = duration

    def trade(self,duration):
        print(f"{self.course} is of duration {duration} months")

obj_DGT = DGT("AIPA")
obj_DGT.trade()
#print(obj_DGT.duration)

obj_NSTIW = NSTIW_Kolkata("COPA")
obj_NSTIW.trade(12)'''

#Multiple Inheritance - 2 parents -> 1 child
'''class Camera:
    def photograph(self):
        print("Clicks photo")
class MusicPlayer:
    def music(self):
        print("Plays songs")
class smartphone(Camera,MusicPlayer):
    def features(self):
        print("smartphone has both camera and music player features.")

obj_sp = smartphone()
obj_sp.features()
obj_sp.music()
obj_sp.photograph()
print("----------------------")
obj_c = Camera()
#obj_c.features() # Attribute error
obj_c.photograph()
print("----------------------")
obj_mp = MusicPlayer()
#obj_mp.features() # Attribute error
obj_mp.music()
'''

#Multilevel Inheritance - 1 Parent -> 1 child -> 1 child
'''class Person:
    def __init__(self,name):
        self.name=name
    def displayname(self):
        print("Employee: ",self.name)

class Employee(Person):
    def EmployeeID(self):
        print("Employee ID: 123")

class Manager(Employee):
    def Salary(self):
        print("Salary: 65000")

obj_manager = Manager("Alex")
obj_manager.Salary()
obj_manager.EmployeeID()
obj_manager.displayname()

obj_emp = Employee("John")
obj_emp.displayname()
obj_emp.EmployeeID()
#obj_emp.salary() # Attribute error

obj_person = Person("Siri")
obj_person.displayname()
'''

#hierarical Inheritance - 1 Parent - 3 child
'''class vehicle:
    def __init__(self,speed):
        self.speed = speed
    def driving(self):
        print("Any vehcile can be inside this")
class car(vehicle):
    def driving(self):
        print("4 wheeler",self.speed, "Km/hr")
class bike(vehicle):
    def driving(self):
        print("2 -wheeler",self.speed, "Km/hr")
class bus(vehicle):
    def driving(self):
        print("6-wheeler", self.speed, "Km/hr")

obj_vehcile = vehicle(45)
obj_vehcile.driving()
print("------------")
obj_car = car(80)
obj_car.driving()'''

# hybrid inheritance - 1 parent - 2 child - 1 child
class Person:
    def display(self):
        print("Person class")
class student(Person):
    def study(self):
        print("student class")
class Teacher(Person):
    def teaching(self):
        print("Tecaher class")
class Courses(student,Teacher):
    def subject(self):
        print("courses class")

obj_courses = Courses()
obj_courses.subject()
obj_courses.teaching()
obj_courses.study()
obj_courses.display()

obj_student = student()
obj_student.study()
obj_student.display()
#obj_student.teaching()
