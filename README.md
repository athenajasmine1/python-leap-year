# python-leap-year
is_leap_year = False
input_year = int(input("Enter the input_year: "))

if input_year % 4 == 0:
    if input_year % 100 == 0:
        if input_year % 400 == 0:
            is_leap_year = True
    else:
        is_leap_year = True


if is_leap_year == True:
         print(input_year, "is leap year")
else:
     is_leap_year == False
     print(input_year, "is not leap year")
