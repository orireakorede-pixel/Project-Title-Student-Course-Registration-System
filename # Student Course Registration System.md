# Student Course Registration System  
# SEN 201 Assignment  
# Name: Michael Ajumobi  
  
# ===============================  
# Student Module  
# ===============================  
student_name = input("Enter student name: Ajumobi Michael ")  
matric_number = input("Enter matric number: 24:14462")  
  
# ===============================  
# Course Module  
# ===============================  
courses = SEN 201, COS 201, GST221, GST 203, MTH 201, CYB 203, CYB 201, ENT 211  
  
print("\nEnter courses to register (type 'done' to finish):done")  
  
while True:  
    course_code = input("Enter course code: ")  
    if course_code.lower() == "done":  
        break  
  
    course_title = input("Enter course title: SOFTWARE ENGINEERING, MATHEMATICS, introduction to cybersecurity, Tech plus")  
    courses.append((course_code, course_title))  
  
# ===============================  
# Registration Module  
# ===============================  
print("\n--- Course Registration Summary ---")  
print("Student Name:", student_name)  
print("Matric Number:", matric_number)  
print("Registered Courses:")  
  
if len(courses) == 0:  
    print("No courses registered.")  
else:  
    for course in courses:  
        print(course[0], "-", course[1])  
  
print("\nRegistration completed successfully.")  
