 class person:
    country = "india"

def takebreath(delf):
    print(" i am brething... ")

class employee(person):
    company = "honda" 

    def getsalary(self):
        print(f"salary is {self.salary}")

    def takebreath(self):
            print("i am employee and i am good")

class programmer(employee):
     company = "fiver"

     def getsalary(self):
                print(f"no salary to programmer")

p = person()
p.takebreath()
e = employee()
pr = programmer()
