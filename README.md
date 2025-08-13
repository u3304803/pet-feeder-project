# pet-feeder-project
feeding_time = "08:00"
bowl_weight = 500

current_time = input("Enter current time (HH:MM): ")

if current_time == feeding_time:
    initial_weight = int(input("Enter bowl weight before feeding: "))
    new_weight = int(input("Enter bowl weight after feeding: "))

    if initial_weight != new_weight:
        print("Feeding successful.")
    else:
        print("Send alert: Bowl weight has not changed!")
else:
    print("Activate sensor: Not feed
<img width="468" height="413" alt="image" src="https://github.com/user-attachments/assets/b8242696-7db1-4799-8dd5-2bb882d13e36" />
