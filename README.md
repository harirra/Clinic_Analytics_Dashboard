# Clinic_Analytics_Dashboard
Interactive clinic analytics dashboard built in Power BI

# 🏥 Clinic Analytics Dashboard — Power BI

## 📌 Project Overview

This project presents an interactive **Clinic Analytics Dashboard** built in Power BI to monitor patient visits, doctor performance, and calendar-based trends.

The dashboard transforms raw clinic data into meaningful visual insights to support decision-making, scheduling efficiency, and operational transparency.

---

## 🎯 Project Significance

Healthcare facilities rely on structured data to improve:

* Patient flow management
* Doctor workload balancing
* Appointment trend tracking
* Operational efficiency

This dashboard demonstrates how business intelligence tools can simplify healthcare analytics and improve visibility into clinic performance.

---

## 🗂 Dataset Structure

The project uses three structured tables:

### 📅 Calendar Table

* Date hierarchy
* Month/Year tracking
* Time-based filtering

Date	MonthNumber	MonthName	MonthNameShort	Day	DayOfWeekNumber	DayOfWeekName	DayNameShort	Year	Quarter	IsWeekend
12/1/2025	12	December	Dec	1	2	Monday	Mon	2025	Q4	No
12/2/2025	12	December	Dec	2	3	Tuesday	Tue	2025	Q4	No
12/3/2025	12	December	Dec	3	4	Wednesday	Wed	2025	Q4	No
12/4/2025	12	December	Dec	4	5	Thursday	Thu	2025	Q4	No
12/5/2025	12	December	Dec	5	6	Friday	Fri	2025	Q4	No
12/6/2025	12	December	Dec	6	7	Saturday	Sat	2025	Q4	Yes
12/7/2025	12	December	Dec	7	1	Sunday	Sun	2025	Q4	Yes
<img width="1684" height="233" alt="image" src="https://github.com/user-attachments/assets/f140c585-f4f4-4e47-8b2b-0399f815e7f8" />


### 🧑‍⚕️ Patient Table

* Patient records
* Visit information
* Appointment details

doctor	doctor_id	department	svg_img	png_img
Barank Obama	DOC001	Cardiology	https://files.chandoo.org/pbix/img/clinic/doctor_01.svg	https://files.chandoo.org/pbix/img/clinic/barank_obama.png
Large Bush	DOC002	Orthopedics	https://files.chandoo.org/pbix/img/clinic/doctor_02.svg	https://files.chandoo.org/pbix/img/clinic/large_bush.png
Fill Clinton	DOC003	Neurology	https://files.chandoo.org/pbix/img/clinic/doctor_03.svg	https://files.chandoo.org/pbix/img/clinic/fill_clinton.png
Donald Roundup	DOC004	General Physician	https://files.chandoo.org/pbix/img/clinic/doctor_04.svg	https://files.chandoo.org/pbix/img/clinic/donald_roundup.png
Now Biden	DOC005	Oncology	https://files.chandoo.org/pbix/img/clinic/doctor_05.svg	https://files.chandoo.org/pbix/img/clinic/now_biden.png
ROWland Reagan	DOC006	Psychiatry	https://files.chandoo.org/pbix/img/clinic/doctor_06.svg	https://files.chandoo.org/pbix/img/clinic/rowland_reagan.png
Jimmy Charter	DOC007	Internal Medicine	https://files.chandoo.org/pbix/img/clinic/doctor_07.svg	https://files.chandoo.org/pbix/img/clinic/jimmy_charter.png
Gerald Find	DOC008	Cardiology	https://files.chandoo.org/pbix/img/clinic/doctor_08.svg	https://files.chandoo.org/pbix/img/clinic/gerald_find.png
<img width="1653" height="262" alt="image" src="https://github.com/user-attachments/assets/1826c777-14e8-4285-8118-66b278f28a0b" />


### 👨‍⚕️ Doctor Table

* Doctor profiles
* Specialization tracking
* Visit associations

Patient_ID	DOB	Gender	Post_Code	Referred_by	In_Date	Out_Date	Doctor_ID	Follow_up
PT0000006	3/14/1959	F	2682	None	12/7/2025	12/7/2025	DOC028	0
PT0000010	4/6/1980	M	629	None	12/7/2025	12/7/2025	DOC004	1
PT0000014	1/21/1983	M	1025	Hamilton	12/31/2025	1/1/2026	DOC002	1
PT0000018	2/7/1971	M	2012	None	12/20/2025	12/21/2025	DOC007	0
PT0000019	11/1/2005	M	930	Taupo	1/16/2026	1/16/2026	DOC023	0
PT0000021	8/28/1995	F	630	Gisborne	1/13/2026	1/13/2026	DOC035	1
PT0000025	1/15/1998	M	618	None	12/26/2025	12/26/2025	DOC035	0
PT0000029	3/29/1977	F	1021	None	12/26/2025	12/26/2025	DOC033	0
<img width="1015" height="262" alt="image" src="https://github.com/user-attachments/assets/aac431ab-c291-4d77-933c-fa6bd9e90de1" />


These tables are linked through relational modeling to enable dynamic reporting.

---

## 🔍 Problem Statements Solved

The dashboard answers key clinic questions:

* How many patients visit over time?
* Which doctors handle the highest workload?
* What are peak appointment periods?
* How does visit volume trend monthly?

---

## 📊 Dashboard Features

* Interactive filters by date and doctor
* Patient visit trend analysis
* Doctor workload comparison
* Dynamic visuals and KPIs

---

## 🛠 Tools Used

* Microsoft Power BI
* Data modeling & relationships
* DAX measures
* Interactive visualization

---

## 🖼 Dashboard Preview

<img width="699" height="376" alt="image" src="https://github.com/user-attachments/assets/673a6649-5fb4-49c9-b47e-9909bac8bbfb" />

----

<img width="958" height="478" alt="image" src="https://github.com/user-attachments/assets/bffaba60-5439-4414-8589-55585343783a" />

---

## ✅ Key Insights

* Identifies peak clinic activity periods
* Highlights doctor utilization patterns
* Enables time-based performance tracking
* Supports data-driven clinic decisions

---

## 🚀 Conclusion

This project showcases how Power BI can convert raw clinic data into actionable insights. It demonstrates practical skills in data modeling, visualization design, and analytical thinking.

---

## 📁 Repository Contents

Clinic_Dashboard.pbix → Power BI dashboard file
calendar.csv → Date dimension data
patients.csv → Patient dataset
doctors.csv → Doctor dataset

---

---

