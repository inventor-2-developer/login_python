
def login():  # This is my user created login  function
        user_first_name()                          # I am calling another function that I made
                                                   # this function calls the last name function
                                                   # the last name function call the email function
                         

def user_first_name():
        first_name = input(" Please enter your First name   ")
        first_name = first_name.casefold()         # Cleaning up the name for the database
        first_name = first_name.capitalize()
        print(first_name)
        first_name = first_name.isalpha()
        print(first_name)

        while first_name == False:                 # If any of these values are false then the loop continues until both are true
            first_name = input(" Please enter your First name   ")
            first_name = first_name.casefold()
            first_name = first_name.capitalize()
            first_name = first_name.isalpha()
        if (first_name == True):                   # If the above values are true then it goes to entering the email
            user_last_name()



def user_last_name():
        last_name = input(" Please enter your Last name   ")
        last_name = last_name.casefold()           # cleaning up the name for the database
        last_name = last_name.capitalize()
        last_name = last_name.isalpha()

        while last_name == False:                  # If any of these values are false then the loop continues until both are true
            last_name = input(" Please enter your Last name   ")
            last_name = last_name.casefold()
            last_name = last_name.capitalize()
            last_name = last_name.isalpha()
        if (last_name == True):
            email_address()


def email_address():
        user_email = input("Please enter your email")
        user_email = user_email.find("@")              # verifying the input of the email address
        while user_email < 2:  # Checking for an "@" sign
            user_email = input("Please enter your email")
            user_email = user_email.find("@")
        if (user_email >= 2):
            print("Here we are ")

# def hotel_information():


Start = int(input('Welcome our Hotel. Are you ready to begin?\n' + ' (Press 1 for Yes)'))
while Start != 1:
          Start = int(input('Invalid response. Welcome to our Hotel. Are you ready to begin? \n ' + '1 for yes and 2 for no'))
if Start == 1:  # if start equals 1 we will begin
            login()
