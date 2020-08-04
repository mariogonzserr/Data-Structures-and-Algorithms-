import random
def guess_my_number(total_tries, start_range, end_range):
    if start_range>end_range:
        start_range, end_range=end_range,start_range
       
    random_number=random.randint(start_range, end_range)
    success_message=("Congratulations")
    failure_message=("Wrong, theres no more tries")
    miss_message=("Sorry, try again")
    
    num_tries=0
    while num_tries<total_tries:
        attempt=int(input("guess the number")) 
        if attempt==random_number:
            print(success_message)
            return
        print(miss_message)
        if attempt>random_number:
            print("Go Lower")
        else:
            print("go Higher")
        num_tries +=1
    print(failure_message)
