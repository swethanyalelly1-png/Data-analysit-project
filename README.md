# Data-analysit-project
print("CUSTOMER CHURN ANALYSIS")
print("-----------------------")

call_duration = int(input("Enter call duration: "))
complaints = int(input("Enter number of complaints: "))
recharge = int(input("Enter recharge frequency: "))

if complaints >= 3 or recharge <= 2:
    print("Customer is At Risk")
    print("Offer a special recharge plan")
else:
    print("Customer is Loyal")
    print("Give loyalty rewards")