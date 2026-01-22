# Student Course Registration System  
# SEN 201 Assignment  
# Name: AJUMOBI MICHAEL OLUSEGUN  
# Matric Number: 24/14462  
  
# ===============================  
# Student Module  
# ===============================  
student_name = "AJUMOBI MICHAEL OLUSEGUN"  
matric_number = "24/14462"  
  
# ===============================  
# Course Module  
# ===============================  
courses = [  
    ("GST 203", "General Studies"),  
    ("SEN 221", "Software Engineering II"),  
    ("CYB 203", "Cybersecurity II"),  
    ("CYB 201", "Introduction to Cybersecurity"),  
    ("GST 221", "Entrepreneurship Studies"),  
    ("COS 201", "Computer Organization")  
]  
  
# ===============================  
# Registration Module  
# ===============================  
print("---- Student Course Registration System ----\n")  
print("Student Name:", student_name)  
print("Matric Number:", matric_number)  
print("\nRegistered Courses:")  
  
for course in courses:  
    print(course[0], "-", course[1])  
  
print("\nRegistration completed successfully.")  
