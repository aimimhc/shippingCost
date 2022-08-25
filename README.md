# shippingCost
weight = 41.5

#Ground shipping
if weight <= 2:
  cost = 20+(weight*1.5)
elif weight <= 6:
  cost = 20+(weight*3)
elif weight <= 10:
  cost = 20+(weight*4)
else:
  cost = 20+(weight*4.75)
print("Cost of shipping (Ground shipping): $", cost)

#Grand Shipping Premium
cost_ground_premium = 125.00
print("Cost of shipping (Ground shipping premium): $", cost_ground_premium)

#Drone Shipping
if weight <= 2:
  cost_drone = weight*4.5
elif weight <= 6:
  cost_drone = weight*9
elif weight <= 10:
  cost_drone = weight*12
else:
  cost_drone = weight*14.25
print("Cost of shipping (Drone shipping): $", cost_drone)
