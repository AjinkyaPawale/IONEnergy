# IONEnergy

##Relation between Grid status and SOC:
● Grid status is a categorical column with classes 1 and 0.
● SOC is a numeric data with max value as 1 and min value as -0.15.

Explanation: The reason we use boxplot is because one of the columns is categorical i.e. Grid
status. Box plot gives the distribution of data in quartiles. From the above two plots we can say
that the majority of data points in Grid status = 0 lie between SOC values of 0.62 and 0.43. Also,
the majority of data points in Grid status = 1 lie between SOC values of 1 and 0.62.

##Relation between Equivalent cycles and SOH:
● Equivalent cycles is a numeric column with min value of 0 and max value of 107.84.
● SOH is a numeric column with min value of 0.919 and max value of 1.


Explanation: From the above figure we can say that there is a strong negative correlation
between SOH and Equivalent cycle. As the value of SOH increases there is a decrease in the
value of Equivalent cycle. For SOH =1 the value of Equivalent cycle = 0.

##Relation between Temperature and SOC:
● SOC is a numeric data column with max value as 1 and min value as -0.15.
● Temperature is a numeric data column with max value136.118 of and min value of
20.26.

Explanation: Here we cannot exactly determine the relation between the two columns.
Although, we can comment about certain trend in the pattern above. For SOC values of
0.8 to 1 the Temperature is always between 18 and 36 approximately. Also, the trend
between Temperature and SOC repeats after certain intervals. For example check the
distribution for temperature values 45 to 58, 70 to 80, 125 to 138.
