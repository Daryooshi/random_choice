# random_choice
import random

names = input("Give me every body names, separated by comma. ")
names_list = names.split(", ")

count_names = len(names_list)
random_choice = random.randint(0, count_names - 1)

title_name = names_list[random_choice].title()

#we can also use of block 13 insted of block 7 and 8
#title_name = random.choice(names_list).title()

print(f"{title_name} is who chosen by this program.")
