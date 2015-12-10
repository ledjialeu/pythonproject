#computepay 
hrs = raw_input("Enter Hours:")
rate = raw_input("Enter rate:")
supp = raw_input("Enter supp hours:")
mult = raw_input("Enter multiplier:")
h = float(hrs)
r = float(rate)
s = float(supp)
m = float(mult)
a = 40
if h <= a:
    pay = h*r
    print pay
else:
    pay = (h-s)*r + s*m*r
    print pay