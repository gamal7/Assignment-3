# Assignment-3
Line Plot
import matplotlib.pyplot as plt

fig = plt.figure()
plt.plot([1,2,3,4])
plt.ylabel('some numbers')
fig.savefig("plot.png")
Bar Plot
import pandas as pd
import matplotlib

df = pd.DataFrame({ 'sample':['foo','bar','qux'], 'score':[5,9,7]})
sum_df = df.groupby("sample").sum()
bar_chart = sum_df.plot(kind="bar")

fig = bar_chart.get_figure()
fig.savefig("plot.png") as Markdown
Rendered as Markdown
Rendered as Markdown
