# Sample data: dictionary with member names and number of books borrowed
records = {1,2,3,4,0,5,3,0}
    
# 1. Compute average number of books borrowed
average=sum(records)/len(records)

# 2. Find book with highest and lowest borrowings (excluding 0 from min)
non_zero_values = [val for val in records if val > 0]
max_borrow = max(records)         # Include all for max
min_borrow = min(non_zero_values)          # Exclude 0 for min

# 3. Count members who have not borrowed any books
zero_borrow=list(records).count(0)

# 4. Most frequently borrowed book count (mode), excluding 0
from collections import Counter
non_zero_values = [val for val in records if val > 0]
freq = Counter(non_zero_values)
most_common = freq.most_common(1)[0][0]

print("Average books borrowed:", average)
print("Maximum books borrowed by any member:", max_borrow)
print("Minimum books borrowed by any member (excluding zero):", min_borrow)
print("Members who borrowed 0 books:", zero_borrow)
print("Most frequently borrowed count (mode, excluding zero):", most_common)
