# task_1-KBC

menu="""

                    Let's Play Kaun Banega Carodepati !!!

"""
print(menu)


print("------------------------------------------------")



def q1():
    q1="Most popular cricater?"
    q1_option="Jadeja","Shami", "K L Rahul", "Virat Kolhi"
    print(q1)
    print(q1_option)
    ans=input("Enter you answer:-")
    if ans=="virat kolhi":
        print("Right answer you have won Rs. 500")
        print("------------------------------------------------")
        q2()
    else:
        print("Wrong answer.") 

def q2():
    q2="Which city is knowns as pink city?"
    q2_option="Ahmedabad","jaipur", "Gandhinagar", "Rajkot"
    print(q2)
    print(q2_option)
    ans=input("Enter your answer:-")
    if ans=="jaipur":
        print("Right answer you have won Rs.1000")  
        print("------------------------------------------------") 
        q3()  
    else:
        print("Wrong answer")

def q3():
    q3="Who wrote the national anthem?"
    q3_option="Mahatma Gandhi","Veer Shivaji", "Lalbahadur Shashtri", "Rabindranath Tagor"
    print(q3)
    print(q3_option)
    ans=input("Enter your answer:")
    if ans=="rabindranath tagor":
        print("Right answer you have won Rs.5000")
        print("------------------------------------------------")
        q4()
    else:
        print("Wrong answer.")
    
def q4():
    q4="How many states are there in INDIA?"
    q4_option="21","22", "27", "28"
    print(q4)
    print(q4_option)
    ans=int(input("Enter your answer:"))
    if ans=="28":
        print("Right answer you have won Rs.10000")
        print("------------------------------------------------")
        q5()
    else:
        print("Wrong answer.")
    

def q5():
    q5="Where is India Gate located?"
    q5_option="Delhi","jaipur", "Gandhinagar", "Rajasthan"
    print(q5)
    print(q5_option)
    ans=(input("Enter your answer:"))
    if ans=="delhi":
        print("Right answer you have won Rs.20000")
        print("------------------------------------------------")
        q6()
    else:
        print("Wrong answer.")
    
def q6():
    q6="Where is Taj Mahal located?"
    q6_option="Delhi","jaipur", "Agra", "Rajasthan"
    print(q6)
    print(q6_option)
    ans=input("Enter your answer :")
    if ans == "agra":
        print("Rigth answer you have won Rs.40000")
        print("------------------------------------------------")
        q7()
    else:
        print("Wrong answer")

def q7():
    q7="Who of father of nation?"
    q7_option="Mahatma Gandhi","Veer Shivaji", "Lalbahadur Shashtri", "Rabindranath Tagor"
    print(q7)
    print(q7_option)
    ans=input("Enter your answer :")    
    if ans=="mahatma gandhi":
        print("Right answer you have won Rs.80000")
        print("------------------------------------------------")
        q8()
    else:
        print("Wrong answer")

def q8():
    q8="Who is the present Prime Minister of INDIA?"
    q8_option="Manmohan Singh","Indira Gandhi", "Narendra Modi", "Amit Shah"
    print(q8)
    print(q8_option)
    ans=input("Enter your answer :")
    if ans == "narendra modi":
        print("Right answer you have won Rs.160000")
        print("------------------------------------------------")
    else:
        print("Wrong answer")

q1()
q2()
q3()
q4()
q5()
q6()
q7()
q8()
