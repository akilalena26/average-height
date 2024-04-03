# average-height
# Input a Python list of student heights
student_heights = input().split()
for n in range(0, len(student_heights)):
  student_heights[n] = int(student_heights[n])
sum = sum(student_heights)
print(f'total height = {sum}')
num = len(student_heights)
print(f'number of students = {num}')
average = sum/num
avg = round(average)
print(f'average height = {avg}')
hh = max(student_heights)
print(f'The highest score in the class is: {hh}')
