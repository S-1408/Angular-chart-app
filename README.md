# AngularChart
![Screenshot (4)](https://user-images.githubusercontent.com/60258353/95459792-f8a77d00-0928-11eb-8113-6641c871040f.png)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.2.

## Steps
1-Configure Chart.js and ng2-charts Library in Angular(npm install ng2-charts chart.js --save).
2- Import ChartsModule in app.module.ts file.

## ng2-Chart properties

1-data (SingleOrMultiDataSet) = set of points of the chart, it should be MultiDataSet only for line, bar, radar and doughnut, otherwise SingleDataSet.
2-datasets ({ data: SingleDataSet, label: string }[]) = data see about, the label for the dataset which appears in the legend and tooltips.
3-labels (Label[]) = x axis labels. It’s necessary for charts: line, bar and radar. And just labels (on hover) for charts: polarArea, pie and doughnut. Label is either a single
4-string, or it may be a string[] representing a multi-line label where each array element is on a new line.
5- chartType (ChartType) = indicates the type of charts, it can be: line, bar, radar, pie, polarArea, doughnut.
6-colors (Color[]) = data colors, will use default and|or random colors if not specified.
7-legend: (boolean = false) = if true show legend below the chart, otherwise not be shown.


