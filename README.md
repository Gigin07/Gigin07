import datetime
current_time = datetime.datetime.now()
print(current_time)
specific_time = datetime.datetime(2023, 7, 9, 12, 30, 0)  # Year, Month, Day, Hour, Minute, Second
print(specific_time)
formatted_time = current_time.strftime("%Y-%m-%d %H:%M:%S")  # Formatting options
print(formatted_time)
# Calculate the difference between two time objects
time_difference = specific_time - current_time
print(time_difference)

# Add or subtract time from a time object
new_time = specific_time + datetime.timedelta(days=7)  # Adding 7 days to specific_time
print(new_time)
