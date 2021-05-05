# FinalProject
Final project for IT 1000
 
For my final project in IT 1000, I want to share a bit about myself

My name is Christopher Garrett, and this is my second semester here at Mizzou. Though I have not attended any classes in-person this semester, I am excited to get back to school next semester. There are plenty of things I would like to share about myself.

## About ME

* [School](School.md)
* [Hobbies](Hobbies.md)
* [Family](Family.md)
* [Baseball](Baseball.md)

## Example Code
Finally, I want to share a piece of code I wrote for one of my IT courses this semester.

```
def user_float(prompt):
    while True:
        try:
            value = float(input(prompt))
            break
        except ValueError:
            print("The value entered is not a floating point number. Please try again.")
    return value

def main():
    radius = user_float("What is the radius of the cylinder? ")
    height = user_float("What is the height of the cylinder? ")

    volume = 3.1415 * radius ** 2 * height

    print("The volume of the cylinder is", volume)

main()
```


