# CPS Dashboard
Display economic and social indicators found in Current Population Survey microdata.

------

January 11, 2019

Contact: Brian Dew, email: brianwdew@gmail.com; twitter: @bd_econ


### Draft list of indicators

- Employed share of 25-54 year olds
- Unemployment rate
- One-year jobfinding rate
- Labor force participation rate
- Share of population that is not in the labor force due to disability or illness
- Occupational group share of employed
- Industry group share of employed
- Unemployment rate by group
- Employment rate by group
- Real usual weekly earnings - first decile
- Real usual weekly earnings - first quartile
- Real usual weekly earnings - median
- Real usual weekly earnings - third quartile
- Real usual weekly earnings by group
- State-level employment indicators (1 year)
- State level wage indicators (2 year)
- MSA-level employment indicators (2 year)
- MSA-level wage indicators (3 year)
- Union membership rate
- Union member growth
- Employment rates including care roles
- Multiple jobholding rate
- Self-employment rate
- Part-time employment rates by reason
- Unemployment rate by reason
- Unemployment rate by duration
- Young people, school enrollment and work
- Reasons for labor force non-participation
- Age share of population
- Education share of population
- Share of workers usually working overtime
- Distribution of work hours over time


(Suggestions welcome!)



### Early thoughts on how to do this

The bd_CPS is in pretty good shape and will serve as the engine for making calculations. However, I would prefer the end result to be a pdf file generated in LaTeX. Interactive web graphics are nice, but they look completely different depending on the screen size and browser, which just makes using them for a large scale project too much of a lift for one guy doing this without pay. 

I'd like the PDF to be colorful and possibly even have a 1958/1959/1960 Topps baseball card look. 

To make this easier, I'll divide the main task into several projects and each project will contain a bunch of issues. That will serve later as my notes. 

Version 0.1 will be a one-page sample pdf file and the python code that generates its data. Once the number of graphics and tables grows, I will include a table of contents. I'd also like to (eventually) have a section of the document dedicated to describing how the calculations are made.
