# alarm-clock-project
Python-based Alarm Clock application using time module, loops, and conditional statements
import time

print("=== ALARM CLOCK ===")

alarm_time = input("Enter alarm time (HH:MM:SS): ")

while True:
    current_time = time.strftime("%H:%M:%S")
    print("Current Time:", current_time)

    if current_time == alarm_time:
        print("\nALARM! WAKE UP!")
        break

    time.sleep(1)