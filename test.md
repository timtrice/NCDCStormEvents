# test
Tim Trice  
January 13, 2016  


```r
library(data.table)

attitude <- attitude
```


```r
library(knitr)
kable(attitude, align = "c")
```



 rating    complaints    privileges    learning    raises    critical    advance 
--------  ------------  ------------  ----------  --------  ----------  ---------
   43          51            30           39         61         92         45    
   63          64            51           54         63         73         47    
   71          70            68           69         76         86         48    
   61          63            45           47         54         84         35    
   81          78            56           66         71         83         47    
   43          55            49           44         54         49         34    
   58          67            42           56         66         68         35    
   71          75            50           55         70         66         41    
   72          82            72           67         71         83         31    
   67          61            45           47         62         80         41    
   64          53            53           58         58         67         34    
   67          60            47           39         59         74         41    
   69          62            57           42         55         63         25    
   68          83            83           45         59         77         35    
   77          77            54           72         79         77         46    
   81          90            50           72         60         54         36    
   74          85            64           69         79         79         63    
   65          60            65           75         55         80         60    
   65          70            46           57         75         85         46    
   50          58            68           54         64         78         52    
   50          40            33           34         43         64         33    
   64          61            52           62         66         80         41    
   53          66            52           50         63         80         37    
   40          37            42           58         50         57         49    
   63          54            42           48         66         75         33    
   66          77            66           63         88         76         72    
   78          75            58           74         80         78         49    
   48          57            44           45         51         83         38    
   85          85            71           71         77         74         55    
   82          82            39           59         64         78         39    


```r
library(stargazer)
```

```
## 
## Please cite as: 
## 
##  Hlavac, Marek (2015). stargazer: Well-Formatted Regression and Summary Statistics Tables.
##  R package version 5.2. http://CRAN.R-project.org/package=stargazer
```

```r
stargazer(attitude, type = "latex")
```


% Table created by stargazer v.5.2 by Marek Hlavac, Harvard University. E-mail: hlavac at fas.harvard.edu
% Date and time: Wed, Jan 13, 2016 - 5:14:35 PM
\begin{table}[!htbp] \centering 
  \caption{} 
  \label{} 
\begin{tabular}{@{\extracolsep{5pt}}lccccc} 
\\[-1.8ex]\hline 
\hline \\[-1.8ex] 
Statistic & \multicolumn{1}{c}{N} & \multicolumn{1}{c}{Mean} & \multicolumn{1}{c}{St. Dev.} & \multicolumn{1}{c}{Min} & \multicolumn{1}{c}{Max} \\ 
\hline \\[-1.8ex] 
rating & 30 & 64.633 & 12.173 & 40 & 85 \\ 
complaints & 30 & 66.600 & 13.315 & 37 & 90 \\ 
privileges & 30 & 53.133 & 12.235 & 30 & 83 \\ 
learning & 30 & 56.367 & 11.737 & 34 & 75 \\ 
raises & 30 & 64.633 & 10.397 & 43 & 88 \\ 
critical & 30 & 74.767 & 9.895 & 49 & 92 \\ 
advance & 30 & 42.933 & 10.289 & 25 & 72 \\ 
\hline \\[-1.8ex] 
\end{tabular} 
\end{table} 
