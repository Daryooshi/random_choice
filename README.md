# random_choice
import random

names = input("Give me evry body names, separated by comma. ")
names_list = names.split(", ")

count_names = len(names_list)
random_choice = random.randint(0, count_names - 1)

title_name = names_list[random_choice].title()

#we can write code even without block 7 and 8
#choice_random_name = random.choice(names).title()

print(f"{title_name} is who chosen by this program.")
