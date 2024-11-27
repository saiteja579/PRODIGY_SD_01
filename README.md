# PRODIGY_SD_01
import matplotlib.pyplot as plt

# Sample data: Age group distribution in millions
age_groups = ["0-14", "15-24", "25-54", "55-64", "65+"]
population_in_millions = [2000, 1300, 3500, 700, 800]

# Create a bar chart
plt.figure(figsize=(10, 6))
plt.bar(age_groups, population_in_millions, color='skyblue')
plt.title("Population Distribution by Age Group")
plt.xlabel("Age Group")
plt.ylabel("Population (in millions)")
plt.grid(axis='y', linestyle='--', alpha=0.7)

# Display the chart
plt.show()
