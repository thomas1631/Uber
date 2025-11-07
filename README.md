<img width="300" height="200" alt="Uber-Logo wine" src="https://github.com/user-attachments/assets/9bdfd652-5a68-4b2a-9f62-c0139afbac31" />

# 🚘**Uber Ride Performance Report**

## 📄 **Client Background**

UberRide is a mobility service platform providing on-demand ride-sharing solutions to users across various regions. The platform connects passengers with drivers for both personal and business travel needs. In recent years, UberRide has experienced notable growth in trip volume, catering to a wide range of trip purposes including meetings, meals, errands, and customer visits.

The dataset used in this analysis covers 1,200+ completed trips across various cities, capturing detailed trip-level information such as trip duration, distance, purpose, category (Business vs Personal), time-of-day, and geolocation metadata. This dataset enables a deep understanding of rider behavior and operational trends.

In collaboration with the Business Operations team, a comprehensive analysis was conducted to uncover usage trends and provide actionable insights for trip demand planning, product positioning, and strategic scheduling. The purpose of this analysis is to inform near-term business decisions and provide clear recommendations for enhancing service delivery, optimizing driver deployment, and improving data quality.

## ⭐ **North Star & Supporting Metrics** 

<ul><li>Bookings per Week – The core operational metric that reflects platform usage frequency and engagement over time. It enables identification of demand surges, ride seasonality, and supports driver supply alignment.</li></ul>

<ul><li>Booking Volume Trends – Tracking the number of bookings over time to identify peak demand periods, seasonal fluctuations, and opportunities for driver scheduling optimization.</li></ul>

<ul><li>Trip Purpose Analysis – Evaluating the distribution of ride purposes (e.g., meetings, errands, client visits) to uncover user behavior patterns and guide service and product alignment.</li></ul>

<ul><li>Category Utilization – Measuring the proportion of business vs personal rides to inform marketing strategies and tailor offerings for high-value segments.</li></ul>

<ul><li>Location Intelligence – Identifying top start and stop locations to enhance operational coverage, reduce wait times, and prioritize service expansion in high-traffic areas.</li></ul>

<ul><li>Data Quality Monitoring – Quantifying and visualizing the frequency of unknown or missing location data to assess system integrity and prioritize corrective actions.</li></ul>

## 📊 **Executive Summary** 
### **Ride Volume Analysis (2016)**
**1. Ride Growth and Peak Performance**

<ul><li>Ride volume in Q4 2016 showed strong growth, with December reaching the highest number of trips (146), highlighting an upward trend in ride demand toward year-end.</li></ul>

<ul><li>Sustained increases were observed across October–December, likely driven by work commitments, holiday travel, and increased city movement.</li></ul>

**2. Sudden Decline in Early Fall**

<ul><li>A noticeable drop occurred in September (only 36 trips)—a significant outlier relative to adjacent months.</li></ul>

<ul><li>This anomaly may stem from data syncing issues, GPS signal loss, or input validation problems, as also indicated by a spike in 'Unknown Start Locations' (69.4%) during that period.</li></ul>

**3. Weekly Demand Patterns & Seasonal Behavior**

<ul><li>Weekly trip analysis shows clear weekday business-hour spikes, especially during afternoons and evenings, indicating work-related travel patterns.</li></ul>

<ul><li>Weekends and early mornings display lower ride volumes, suggesting lower personal or leisure use.</li></ul>

## 📊 **Insights Deep-Dive** 
**1. Weekly Bookings Trend**

<img width="1032" height="278" alt="Screenshot 2025-11-07 095524" src="https://github.com/user-attachments/assets/1bba48c9-4b03-4ef9-b496-1ec8152a588f" />

<ul><li>Weekly ride patterns reveal consistent weekday spikes, primarily Tuesday to Thursday, aligning with business commute needs.</li></ul>

<ul><li>A noticeable dip is seen around early September, possibly due to data issues (e.g., high “Unknown Start” locations) or external disruptions.</li></ul>

**2. Category Distribution**

<img width="482" height="282" alt="image" src="https://github.com/user-attachments/assets/5fd81d21-b670-42dd-96f4-e073add81c52" />

<ul><li>Over 93% of all trips are categorized as Business, highlighting UberRide’s strong usage in corporate travel.</li></ul>

<ul><li>Personal ride usage is minimal, indicating potential for service expansion or targeting.</li></ul>

**3. Trip Purpose Utilization**

<img width="813" height="262" alt="image" src="https://github.com/user-attachments/assets/d6aee7a3-2b35-4526-ba7f-2d3de753b32b" />

<ul><li>The top ride purposes include Meetings, Meal/Entertain, and Errand/Supplies.</li></ul>

<ul><li>Customer Visit and Temporary Site are also notable, suggesting recurring inter-office travel or field operations.</li></ul>

**4. Start & Stop Location Hotspots**

<img width="372" height="292" alt="image" src="https://github.com/user-attachments/assets/c89ea9c1-d6b7-437b-b8b0-a170419666df" />

<img width="372" height="324" alt="image" src="https://github.com/user-attachments/assets/ea32c18e-c456-446c-bcde-0b1d3932f862" />

<ul><li>Cary, Morrisville, and Unknown are the most frequent start/stop cities.</li></ul>

<ul><li>High occurrence of "Unknown" indicates a gap in data capture—important for route optimization and city-level coverage decisions.</li></ul>

**5. Missing Location Data**

<img width="494" height="250" alt="Screenshot 2025-11-07 100904" src="https://github.com/user-attachments/assets/b339c7d1-f317-4128-bd03-6f47b7e47f7b" />

<img width="888" height="370" alt="Screenshot 2025-11-07 100627" src="https://github.com/user-attachments/assets/351f6197-f7f2-43ca-b5ab-a07b44cf4000" />

<ul><li>12.81% of rides have an unknown or missing start location.</li></ul>

<ul><li>September alone shows an extreme 87.19% unknown starts, signaling possible technical or data syncing issues.</li></ul>

<ul><li>Consistent location data is vital for route optimization and trust in ETA predictions.</li></ul>
