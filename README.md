# Height-Caluclation
Height = input("How many feet are you: ")
Unit = input("inches or centimeters: ")
if Unit == "inches":
    result = float(Height) * 12
    print("Height in inches " + str(result))
elif Unit == "centimeters":
    result = float(Height) * 30.48
    print("Height in cm " + str(result))
