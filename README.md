# Census Attribute Frequency

A dataset with csv format contains census results with the following attributes:
1. Age
2. Sex
3. Education
4. Native Country
5. Race
6. Marital Status
7. Work Class
8. Occupation
9. Hours per week
10. Income
11. Capital Gain
12. Capital Loss

Each of above attribute has more than one unique value.
The task is to provide an algorithm that can filter sets of attributes and its value which have certain appearance frequency above given threshold value.
The set may contain of more than one attribute depending on the input.

*For Example:*

If I would like to know, sets of 2 attributes that have more than 0.7 appearance frequency, the algorithm will returns (only for example, not the real result):

>'native-country=United-States', 'race=White'

>'race=White', 'capital-gain=None'
