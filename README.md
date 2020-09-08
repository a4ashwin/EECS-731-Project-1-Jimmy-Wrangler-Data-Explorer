# EECS-731-Project-1-Jimmy-Wrangler-Data-Explorer
 1st assignment of EECS 731 Intro to Data Science - Covid 19 cases in US vs global

 Prerequisites
 Anaconda, Python 3.7.3, Jupyter Notebook, Pandas Library

 Introduction
 Corona Virus is spreading widely in the whole world and the situation is getting worse day by day. We have got the global data of covid19 cases and US's data from kaggle.com. US's data has covid19 cases and deaths from 01-21-2020 to 08-28-2020 and global data has it from 01-21-2020 to 07-27-2020. We are going to find the rise and fall in percentage of US population got affected from covid19 and also the people who died in contrast with the World's population.


 Process
 We have combined US covid19 data and global data on the basis of date.
 We have removed the outliers in US's data from 07-28-2020 to 01-21-2020 as it is not needed in the calculation of percentage.
 We calculated two columns namely "US cases %" and "US Deaths %" on the basis of US formula P= US data/Global data * 100
 We have saved the data in CSV.
 We have plotted graph of the raise and fall of Percentage US covid19 affected people and percentage of people who died because of Covid19.

 Result
 The result shows the comparison of Covid-19 cases and deaths with respect to the total cases and deaths in the world. The first case in US was registered on 01-22-20 and the rest of the world had 555 cases till then. The first death was registered from Covid-19 was registered on 02-29-20 and the world had 2936 deaths till then. On 03-01-20, US had a Covid-19 case and death of around 0.1 percent. By the end of March, the cases % raised to 21.62% and the death % raised to 9.67% of the entire world. Till 04-05-20 the % of cases increased rapidly and then got increasing less with respect to the world but the death % still increasing rapidly. On 05-03-20, cases % went to the highest of 33.14% with respect to the rest of the world and the death % went highest to 28.36% on 05-20-20. After that, the % of cases and deaths got stable and then started decreasing slightly. The analysis shows that from 03-12-20 to 05-03-20, Covid-19 spread in US very rapidly then the rest of the world. Major countries like India and China, Iran, UK etc had full lockdown at that period while US government didn't impose any lockdown of time and that may be a reason for US to have a huge spike in Covid-19 cases. After 03-05-20, many countries have also revoked lockdown and that can be the reason that the rate of Corona infection became nearly stable and then starts decreasing in USA with the rest of the world.


 Built With
 Jupyter Notebook
 Python 3.7.3
 Pandas


 Authors
 Ashwin Rathore

 License
 This project is licensed under the MIT License - see the LICENSE.md file for details

 Acknowledgments
 https://www.kaggle.com/imdevskp/corona-virus-report?select=day_wise.csv
 https://www.kaggle.com/joelhanson/coronavirus-covid19-data-in-the-united-states?select=us-states.csv
