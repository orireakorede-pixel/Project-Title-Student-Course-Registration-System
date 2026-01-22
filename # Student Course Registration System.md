# Student Course Registration System  
# SEN 201 Assignment  
# Name: Michael Ajumobi  
  
# ===============================  
# Student Module  
# ===============================  
student_name = input("Enter student name: ")  
matric_number = input("Enter matric number: ")  
  
# ===============================  
# Course Module  
# ===============================  
courses = []  
  
print("\nEnter courses to register (type 'done' to finish):")  
  
while True:  
    course_code = input("Enter course code: ")  
    if course_code.lower() == "done":  
        break  
  
    course_title = input("Enter course title: ")  
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
