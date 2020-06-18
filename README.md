# creatingChartsAutomated
Preparing chart data and chart itseld automatic

To create chart we have to create table that contains data. This data is updated weekly. Data is taken from primavera database.

So when primavera database changes, we have to change our excel table accordingly. 
First, we export particular data from primavera as html. 
Then this code starts working. It converts html to excel, converts to a desired format, deletes unnecessary columns and row.
Sometimes primavera does not export cumulative quantities. In case I keep cumulative quantities with me somewhere, and I have to merge two excel files(This code does this automatically)
After two excels are merged, it creates s-curve charts for every blok of building seperately.

It contains 16 modules.
  adding_picture
  afterFinish
  axisLabels
  beforeStart
  chartNameRowNumber
  chartProductivity
  convertToPDF
  createChart
  FoldersAndFile
  fuzzyMatchFunction (This one I took from internet, I am hot the authow, I do not remember the author, sorry... But we need it :))
  getItReadyModule
  labelPercentage
  lastColumnNumber
  lastXValueOfChart
  synchAllFiles
  totalNumberOfCharts
  
*For some reason, I could not upload excel file. It gives error.
