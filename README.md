[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/CJe7Q6l6)
# MidtermReviewPt1
# TEST DATA - Do not modify
creator_name = "DigitalDreamer"
current_followers = 4567
starting_followers = 2100
days_tracked = 45
milestone_increment = 1000

# YOUR CODE BELOW THIS LINE
# Calculate follower statistics and milestone progress

# Calculate milestone progress
current_milestone = current_followers // milestone_increment
progress_in_milestone = current_followers % milestomne_incremnet

# Calculate growth statistics
total_gained = current_followers - starting_followers
daily_average = total_gained // days_tracked

# Calculate projections
days_to_milestone = (milestone_increment = progress_in_milestone) // daily_average
weekly_growth = daily_average * 7
# Display results with f-strings
print(f"Creator: {creator_name}")
print(f"Current Milestone: {current_milestone}")
print(f"Progress in Milestone: {progress_in_milestone} followers")
print(f"Total Growth: {total_gained} followers")
print(f"Daily Average {daily_average}followers")
print(f"Days to Next Milestone {days_to_milestone}days")
print(f"Weekly Growth Projectetion {weekly_growth} followers")
Task 2
# TEST DATA - Do not modify
account_holder = "Taylor Banks"
starting_balance = 487
withdrawal_amount = 120
atm_fee = 3
monthly_fee = 15
months_inactive = 8

# YOUR CODE BELOW THIS LINE
# Calculate remaining balance after fees and withdrawal
# Calculate how many full $20 bills and remaining dollars

# Subtract withdrawal from balance
balance = starting_balance
balnce-= withdrawal_amount

# Subtract ATM fee
balance -= atm_fee

# Calculate and subtract total monthly fees
total_monthly_fees = monthly_fee * months_inactive
balance -= total_monthly_fees

# Calculate full $20 bills and remaining dollars
full_twenties = balance //20
remaining_dollars = balance %20

# Display results with f-strings
print(f"Account Holder: {account_holder}")
print(f"Remaining Balance:${balance}")
print(f"Full $20 Bills {full_twenties}")
print(f"Remaining Dollars ${remaining_dollars}")
