## Project-2_Prediction_of_bodyfat
### Description
### Context
Body fat prescription
### Null Hypothesis: 
There is no relationship between the percentage of body fat for an individual and the body density.

### Content
The variables listed below, from left to right, are:
1.	Density determined from underwater weighing
2.	Percent body fat from Siri's (1956) equation (class variable)
3.	Age (years)
4.	Weight (lbs)
5.	Height (inches)
6.	Neck circumference (cm)
7.	Chest circumference (cm)
8.	Abdomen 2 circumference (cm)
9.	Hip circumference (cm)
10.	Thigh circumference (cm)
11.	Knee circumference (cm)
12.	Ankle circumference (cm)
13.	Biceps (extended) circumference (cm)
14.	Forearm circumference (cm)
15.	Wrist circumference (cm)


(Measurement standards are apparently those listed in Benhke and Wilmore (1974), pp. 45-48 where, for instance, the abdomen 2 circumference is measured "laterally, at the level of the iliac crests, and anteriorly, at the umbilicus".)

A variety of popular health books suggest that the readers assess their health, at least in part, by estimating their percentage of body fat. In Bailey (1994), for instance, the reader can estimate body fat from tables using their age and various skin-fold measurements obtained by using a caliper. Other texts give predictive equations for body fat using body circumference measurements (e.g. abdominal circumference) and/or skin-fold measurements. See, for instance, Behnke and Wilmore (1974), pp. 66-67; Wilmore (1976), p. 247; or Katch and McArdle (1977), pp. 120-132).
The percentage of body fat for an individual can be estimated once body density has been determined. Folks (e.g. Siri (1956)) assume that the body consists
of two components - lean body tissue and fat tissue. Letting:
•	D = Body Density (gm/cm^3)
•	A = proportion of lean body tissue
•	B = proportion of fat tissue (A+B=1)
•	a = density of lean body tissue (gm/cm^3)
•	b = density of fat tissue (gm/cm^3)
we have:
D = 1/[(A/a) + (B/b)]
solving for B we find:
B = (1/D)*[ab/(a-b)] - [b/(a-b)].
Using the estimates a=1.10 gm/cm^3 and b=0.90 gm/cm^3 (see Katch and McArdle (1977), p. 111 or Wilmore (1976), p. 123) we come up with "Siri's equation":
Percentage of Body Fat (i.e. 100*B) = 495/D - 450.



