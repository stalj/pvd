# DATA VISUALISATION

Data visualization is the art of representing information and data graphically. It transforms complex data into accessible visual forms, making it easier for people to understand trends, patterns, and relationships. A chart, also known as a graph, is a visual representation of data. It allows users to see and understand information more effectively. Charts serve as powerful tools in various contexts, including business, communication, and data visualization. They transform complex data into accessible visual representations, aiding understanding, decision-making, and effective communication.




## Creating Charts from Data Series

1. To use Pandas for creating charts, first you need to download and install the matplotlib library:

    ```
    pip install matplotlib
    ```

1. Open the notebook first-chart.ipynb. Learn how to create a chart in the pandas library. Then, complete all tasks in the notebook.

1. TASK in new notebook



## Creating Charts from DataFrame




tworzenie prostego wykresu - dane źródłowe
dataseries
dataframe - wiele subwykresów
plt.show()


opisywanie wykresu - osie x i y, tytuł wykresu


wybór rodzaju wykresu
df.plot(kind = 'scatter', x = 'Duration', y = 'Calories')
liniowy - domyslny?
scatter
histogram - one column
df["Duration"].plot(kind = 'hist')












