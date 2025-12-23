import pandas as pd
import matplotlib.pyplot as plt
data=pd.read_csv("dvp.csv")
x=data['Year']
y=data['Fraud Rate (per $100 spent)']
plt.bar(x,y)
plt.xlabel("Year")
plt.ylabel("Fraud Rate (per $100 spent)")
plt.title("Credit card frauds plot")
plt.show()