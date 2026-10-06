# Voltage Divider Calculation
# Formula: Vout = Vin * R2 / (R1 + R2)

Vin = float(input("Enter input voltage (V): "))
R1 = float(input("Enter resistance R1 (Ohms): "))
R2 = float(input("Enter resistance R2 (Ohms): "))

if R1 <= 0 or R2 <= 0:
    print("Resistance must be greater than zero.")
else:
    Vout = Vin * R2 / (R1 + R2)

    print("Output Voltage =", round(Vout, 2), "V")