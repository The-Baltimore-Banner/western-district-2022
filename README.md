Western District Group Violence Reduction Strategy Analysis
================
 - [Overview](#overview)
 - [Data](#data)
 - [Methodology](#method)
 - [Limitations](#limitations)
 - [License](#license)
 
 ## Overview
### How we analyzed the available data to access common criticisms of the 33% drop in shootings

For the eighth year in a row, Baltimore surpassed 300 homicides. But the city’s public safety leaders have emphasized one bright spot in an otherwise dismal 2022: a dramatic drop in shootings in one of the most violent parts of town.

The 33% reduction in homicides and nonfatal shootings in the Western District follows Mayor Brandon Scott’s revival of an alternative approach to policing the city’s most violent offenders, piloted in one of its most violent police districts.

For many skeptics, attributing the sudden drop in shootings to the Group Violence Reduction Strategy seems too good to be true. The Baltimore police union and members of the City Council have questioned whether the drop could actually stem from population losses, a heavier police presence or misleading data.

The answer to these questions is core to understanding whether the strategy is working, prompting The Banner to dive deep into Baltimore Police shooting data. What did our analysis show? Some questions remain unanswered, but common critiques don’t hold up.

Read the short version: [Nine charts that help explain last year’s sudden drop in shootings in West Baltimore](https://www.thebaltimorebanner.com/community/criminal-justice/west-baltimore-shootings-2022-crime-stats-guns-RGEBE4R74NBB5NWLKHZIXXNW2E/)

Read the long version: [What caused a 33% drop in gun violence in West Baltimore last year? We analyzed it ](https://www.thebaltimorebanner.com/community/criminal-justice/gvrs-data-gun-violence-data-west-baltimore-XITLPKVQXBAZPH7L3NWJJMJQDU/)

While homicides were relatively steady in 2022 compared to 2021, The Banner chose to analyze the change in shooting incidents to better gauge how often people are choosing to shoot others, a better metric when analyzing the outcomes of a strategy meant to prevent more violence.

This story was published in a long and short version as part of an experiment to condense complex data findings into more easily digestible news story. Have feedback? I'd love to hear it. ryan.little@thebaltimorebanner.com.

<a id="method"></a>

## Methodology
### How we counted shootings and victims, and plotted them around district boundaries

This analysis of Open Baltimore Part 1 crime victims database defines shooting victims differently than the Baltimore Police Department. BPD defines shooting victims as someone who was shot, but not killed. This analysis includes people who were shot and lived, and those who were shot and killed. It does not include people who were shot at but not wounded. BPD defines that as a “shooting at” crime, and does not include it in the Part 1 victim data it releases publicly. The Banner sought to analyze gun violence without taking into account whether the victim lived.

While reviewing this analysis, it is important to remember the difference between the number of shootings and the number of victims. The database includes one row for every victim of a Part 1 crime. To get distinct crimes, we grouped them by time, location and other shared variables. In some cases, a shooting event led to multiple victims, some of whom were killed and others who were wounded. Our analysis counts this as one shooting crime, but multiple shooting victims.

Baltimore City property records were used to identify Gilmor Homes. Neighborhoods and police districts were identified using their respective shapefiles on Open Baltimore. When counting shootings within an X number of blocks of a shapefile, we counted 100 meters for each block in addition to 50 meters for the immediate street. In some parts of the city, this may not be three literal blocks. 

The cleaned 911 and 311 calls database is provided upon request. Please email me at ryan.little@thebaltimorebanner.com.

<a id="limitations"></a>

## Limitations and reproductions
### 

There are known errors in the public Part 1 Crimes Database. The database is also frequently changing. Crimes that were once classified as homicides are often reclassified, making it difficult to recreate mid-year BPD reports at the end of the year. A slight variation is to be expected. 

This analysis relies on a version of the Part 1 Crimes Database generated on Jan. 9, 2023. Using this code to analyze earlier or newer versions should return slightly different results. The Banner intended to use the most recent version available, but that version appears to assign some shootings to a non-existent police district called "sd5". We reverted to the version with which much of the analysis was originally conducted on.

Not every year in the database is reliable. In response to previous questions from The Banner, BPD admitted that shooting data before 2014 should not be relied on. They have never said why. Further analysis has led The Banner to question data in 2014 as well, leaving only the last seven years for analysis. 

The geocoded coordinates may not be exact locations. Some shootings may have literally taken place just inside or just outside the ranges where The Banner looked, but have locations in the data that included or excluded them in error.

Some entries list impossible ages such as negative numbers or very large numbers. The error is less common in shootings and homicides. There are 52 shooting victims who do not have an age listed or have a negative age. About half of these errors are from years before 2017. The number of ageless victims went up in 2022. There were six recorded ageless victims this year, making up 12% of all ageless victims in the city’s data.

<a id="license"></a>

## License

Copyright 2023, The Venetoulis Institute for Local Journalism

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

