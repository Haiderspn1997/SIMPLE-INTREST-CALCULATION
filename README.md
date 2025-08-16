# SIMPLE-INTREST-CALCULATION# Simple Interest Calculator

def simple_interest(principal, rate, time):
    """Function to calculate Simple Interest"""
    return (principal * rate * time) / 100

# Taking inputs from the user
p = float(input("Enter Principal Amount (P): "))
r = float(input("Enter Rate of Interest (R) in %: "))
t = float(input("Enter Time (T) in years: "))

# Calculate Simple Interest
si = simple_interest(p, r, t)

# Display result
print("\n------- Simple Interest Calculation -------")
print(f"Principal Amount (P) : {p}")
print(f"Rate of Interest (R) : {r}%")
print(f"Time (T)             : {t} years")
print("-------------------------------------------")
print(f"Simple Interest (SI) : {si:.2f}")
print(f"Total Amount (A)     : {p + si:.2f}")
