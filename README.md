# Hospital Analytics Dashboard
An interactive, end-to-end Hospital Analytics Dashboard designed to analyze and monitor healthcare performance metrics, patient satisfaction, and operational efficiency. This project helps healthcare administrators, hospital management, and analysts derive actionable insights from patient records and hospital service indicators.

## Project Overview
This dashboard transforms raw hospital data into insightful visualizations that cover patient demographics, clinical outcomes, financial metrics, and hospital performance indicators.

The analysis aims to:

Optimize hospital operations

Improve patient outcomes and satisfaction

Track resource utilization

Monitor staff and facility performance

Support data-driven healthcare decisions

## Dataset Details
The dataset contains detailed patient-level and hospital-level data with the following key columns:

The dataset contains detailed patient-level and hospital-level data with the following key columns:

| Column | Description |
|--------|-------------|
| `PatientID` | Unique identifier for each patient |
| `Age`, `Gender` | Demographic details |
| `Hospital` | Hospital name or ID |
| `AdmissionDate`, `DischargeDate`, `LengthOfStay` | Admission metrics |
| `Diagnosis`, `TreatmentType`, `TreatmentOutcome` | Medical data |
| `Doctor` | Treating physician |
| `City`, `State` | Geographic information |
| `TotalBill`, `InsuranceCovered`, `PaymentStatus` | Financial data |
| `SatisfactionScore` | Overall patient satisfaction |
| `CleanlinessRating`, `StaffBehaviorRating`, `DoctorCommunication`, `PainManagementRating`, `DischargeInstructionsRating` | Patient feedback on hospital services |
| `MortalityRate` | Rate of mortality per diagnosis/treatment type |
| `RevisitWithin30Days` | Indicator for early readmissions |
| `HospitalAcquiredInfection` | Tracks infection incidents post-admission |


## Dashboard Features
### Home Page
Hospital wise distribution

Patient distribution by city

Patient distribution by insurance

Patient metrics by hospital and city

### Trends
Patient admission trend by hospital

Revist rate by month

Length of stay by month


### Rating
Hospital rating by various parameters

Doctor rating by communication

Satisfaction score vs bill amount

### Finance
Revenue generated by month

Revenue generated by hospital

Satisfaction score vs bill amount

Revenue from Insurance

## Key Insights Explored
Which factors most influence patient satisfaction?

What is the relationship between Length of Stay and Mortality?

Are there specific hospitals or doctors associated with high readmission or infection rates?

How does insurance coverage affect total billing and payment status?

Which hospitals maintain the highest hygiene and communication standards?

## Project Structure

📦 Hospital-Analysis-Dashboard
├── 📂 Data/
│   └── hospital_data.csv
├── 📂 Images/
│   ├── Home Page.png
│   ├── Rating.png
│   ├── Finance.png
│   └── Trends.png
|   └── Custom Tool Tip.png
|   └── Tooltip.png
├── 📄 README.md
└── 📄 Hospital_analysis.pbix
└── 📄 Hospital Analaysis Dashboard.pdf

## How to Run the Project
Clone the repository:

git clone https://github.com/ankheat/Hospital-Analysis-Dashboard.git
Open the dashboard file:

Power BI: Hospital_analysis.pbix

Load the hospital_data.csv as your data source.

Explore the interactive visuals and apply filters.
## Future Enhancements
Real-time data integration via APIs

Predictive modeling for readmission and mortality risk

NLP sentiment analysis from patient feedback

Automated alerts for KPI deviations

Dashboard export and email scheduling features

## Sample Visuals

Home Page

![Home Page](https://github.com/user-attachments/assets/bcc4ac38-02bb-41be-9737-db4ce936f2c8)

Trends
![Trends](https://github.com/user-attachments/assets/20df1946-b538-4922-adb4-8d8b24f0909c)


## Target Users
Hospital Administrators

Clinical Directors

Quality & Compliance Teams

Financial Officers

Healthcare Analysts

## Contributions
Contributions and suggestions are welcome!
Please open issues or submit a PR to add features or fix bugs.

## License
This project is open-source and available under the MIT License.

## Contact
For questions or collaborations, contact ank30.sharma@gmail.com

