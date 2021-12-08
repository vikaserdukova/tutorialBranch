# tutorialBranch
letter_list = [letter for letter in greeting]
print(letter_list)
number_list = [number for number in '0123456789']
print(number_list)
number_list_1 = [num for num in range (0, 10)]
print(number_list_1)
number_list_2 = [num ** 2 for num in range (0, 10)]
print(number_list_2)
number_list_3 = [-((num - 3)/2) ** 2 for num in range (0, 10)]
print(number_list_3)

number_list = [6, 43, -2, 11, -55, -12, -3, 345]
new_list = [number **3/2 for number in number_list if number > 0]
print(new_list)

new_list_1 = ['+' if number > 0 else '-' for number in number_list]
print(new_list_1)

# Dictionary Comprehension
number_dict = { 'first': 2, 'second': 3, 'third': 4}
new_dict = {key: value**3 for key, value in number_dict.items()}
print(new_dict)

number_list = [6, 43, -2, 0, 11, -55, -12, -3, 345]
number_dict ={number: number **2 for number in number_list}
print(number_dict)

number_dict ={number: 'positive' if number >0
else 'neggative' if number < 0 else 'zero' for number in number_list}
print(number_dict)
