
name="emine"
surname="gur"



class student_control():

    def student(self):
        giris = 3
        for i in range(3):
            fname = input("Please enter your name:")
            lname = input("Please enter your surname:")
            if giris > 0:
                if name == fname and surname == lname:
                    print("Welcome")
                    break
                else:
                    print("This is false")
                    giris -= 1
                    continue

            print("Please try again later")

    def lesson (self):

        self.list=["machine learning","python","deep learning","math","algorithm"]

        for i in range(len(self.list[0:6])):
            if i>=3 and i<=5:
                print("ders seçimi tamamdır")
                continue
            else:
                print("en az 3 ders seçebilirsiniz:")
                continue
    def result_course(self):
        print("course grade:")

        for i in range(len(self.list)):
            print(f"{i}.{self.list[i]}")
            self.course=input("course for name:")
            self.grade={}
            self.grade=0
            if self.course in self.list:

              midterm=float(input("please midterm note:"))
              final=float(input("Please final note:"))
              project=float(input("Please project note:"))



              self.grades=float(midterm*0.3+final*0.5+project*0.2)
              if self.grades>=90:
                print("AA")
              elif 70<= self.grades <90:
                print("BB")

              elif 50<= self.grades<70:
                print("CC")

              elif 30<=self.grades<50:
                print("DD")
              elif self.grades<30:
                print("FF")
                break
            else:
                print("Error!!!!")









less=student_control()
less.student()
less.lesson()
less.result_course()
