--Total Number of City by Area--
SELECT AreaName, COUNT(CityName)
FROM FP_Area a, FP_City c
WHERE a.City_ID = c.City_ID
Group BY 1


--Total Number Division by Area--

SELECT AreaName, COUNT(DivisionName) 
FROM FP_Area a, FP_Division d 
WHERE a.AreaID = d.AreaID 
Group BY 1 


--Total Number of Line of Business by Division--
SELECT DivisionName, COUNT(LOB_Name) 
FROM FP_LineOfBusiness b, FP_Division d 
WHERE b.DivisionID = d.DivisionID 
Group BY 1 


--Total Number of Job Level by the Line of Business--
SELECT LineOfBusiness, 
COUNT(*) as ant 
From FP_HR.HR_data 
Group by 1 


--Total Number of LOB SubGroup by Line of Group--
SELECT LOB_Name, COUNT(SubGroupName) 
FROM FP_LineOfBusiness b, FP_LOBSubGroup s 
WHERE b.LOB_ID = s.LOB_ID 
Group BY 1 


--Total number of Employee by Job Title--
SELECT `JobTitle`, COUNT(1)
FROM `HR_data` 
GROUP BY 1


--Total number of Employee by LOB SubGroup--
SELECT `LOBSubgroup`, COUNT(*) as ant
FROM `HR_data` 
GROUP BY 1


--Total number of Employee by Membership--
SELECT `ERG_Membership`, COUNT(`FirstName`+
`LastName`)
FROM `HR_data` 
GROUP BY 1


--Summary of Total Salary by Area--
SELECT `WorkArea`, sum( replace(Salary, ",", '')) FROM `HR_data` 
GROUP BY 1 


--Summary of Total Salary by Job Title--
SELECT `JobTitle`, 
sum( replace(Salary, ",", ’’)) 
FROM `HR_data` 
GROUP BY 1 


--Total Salary by Division--
SELECT `WorkDivision`, 
SUM( replace(Salary, ",", ’’)) 
From FP_HR.HR_data 
GROUP by 1


 
