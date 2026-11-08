# ism2411-lab11
# ISM2411 Lab 11 - Customer Dictionary & Lookup
# Alissa Namazbayeva

## How to Run 
From this folder:

```
python3 customers.py
```

# Exercise 1

customer = {
    "name": "Alissa",
    "email": "alissa@example.com",
    "tier": "gold",
    "ytd_spend": 500.00
}

print(customer["name"])
print(customer["email"])
print(customer["tier"])
print(customer["ytd_spend"])

print(customer)

# Exercise 2 

customer["phone"] = "555-123-4567"
print(customer)

customer["tier"] = "platinum"
print(customer)

del customer["email"]
print(customer)