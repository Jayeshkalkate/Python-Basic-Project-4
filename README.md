# Python-Basic-Project-4
By using python programming language .

# Merge Two Lists :-

# Two Blank list

girls_name_list = []
boys_name_list = []

# User input to enter the Girls Names and Boys Names into the list.

number_of_girls_in_class = (int(input("Enter the number of girls in class : ")))
number_of_boys_in_class = (int(input("Enter the number of boys in class : ")))

# Used the for loop to get input from the users multiple times .

for boys_name in range (number_of_girls_in_class) :
    boys_name = (input("Enter your name in boys section : "))
    boys_name_list.append(boys_name)

for girls_name in range (number_of_boys_in_class) :
    girls_name = (input("Enter your name in girls section : "))
    girls_name_list.append(girls_name)

print(f"The list of boys name in class is :\n{girls_name_list}.\nThe list of boys name in class is :\n{boys_name_list}")

# Merage the both Boys Names and Girls Names list
all_students_names_in_class = girls_name_list + boys_name_list

# Display the all the students Names which is Boys Names and Girls Names .
print(f"The all students names into the class is :\n{all_students_names_in_class}")
