
# YouTube Analysis Dashboard (Power BI)

> **Intern ID:** XI082025 &nbsp;&nbsp; **Name:** Roshan Kumar  

![Dashboard Preview](images/dashboard.jpg)

## 📌 Project Overview
Ye repository ek **Power BI–based YouTube Data Dashboard** host karta hai. Iska purpose hai multiple languages aur channels ke across YouTube performance ko analyze karna – jaise **views, subscribers, uploads,** aur **top channels**.

## 🔑 Key Highlights (as shown in screenshot)
- **Subscribers:** ~5.651 **billion** (5,651,593,092)
- **Views:** ~1.071 **trillion** (1,071,312,146,553)
- **Channels:** 4,308
- **Uploaders:** 6,361
- **Filter:** Language slicer (All + specific languages)

> Note: Ye numbers **demo dataset/screenshot** se liye gaye hain. Aap apne data ke hisaab se file refresh/update kar sakte ho.

## 📊 Visuals Included
- **KPI Cards:** Subscribers, Views, Channels, Uploaders  
- **Pie Chart:** *Count of video id by language*  
- **Bar Charts:** *Channel name by uploader*, *Subscriber by channel name*  
- **Scatter Plot:** *View_count by language* (relationship view vs language)  
- **Hierarchy/Decomposition Tree:** *Uploader → Language* drilldown  
- **Slicer:** Language selection

## ❓ Business Questions Answered
1. Konsi **language** sabse zyada **videos/views/subscribers** drive karti hai?  
2. Top **channels** kaun se hain (e.g., T-Series, Zee Music, etc.)?  
3. **Uploaders** ka distribution aur unka contribution kya hai?  
4. **View vs Subscriber** relationship kaisa dikh raha hai?  
5. Kis **video duration / posting pattern** se performance impact hota hai? *(optional, if available)*

## 🧱 Repository Structure
```
root/
├─ PowerBI/
│  └─ YouTube_Analysis_Dashboard.pbix      # main dashboard file
├─ data/
│  ├─ channel_master.csv                   # channel-level data (sample)
│  └─ video_summary.csv                    # video-level data (sample)
├─ images/
│  └─ dashboard.jpg                        # screenshot used in README
└─ README.md                               # this file
```

> Folder/file names aap apne project ke hisaab se rename kar sakte ho.

## 🚀 How to Use
1. **Clone/Download** repository.  
2. `PowerBI/YouTube_Analysis_Dashboard.pbix` ko **Power BI Desktop** me open karo.  
3. **Data Source Settings** me jaakar CSV paths update karo (agar aapke local paths different hain).  
4. **Refresh** data (Home → Refresh).  
5. Slicer aur visuals se **interactive analysis** karo.

## 🔄 Data Refresh Tips
- CSV files ko `data/` folder me replace/update karo.  
- Power BI me **Transform Data → Power Query** me schema validate karo.  
- Null/blank handling, data types (Date/Time, Whole Number, Decimal), aur duplicates pe dhyaan do.  

## 🧭 Assumptions & Notes
- Screenshot ke metrics **sample** data par based hain.  
- Aap apne **organization/client** ka dataset connect karke real-time insights nikaal sakte ho.  

## 🛣️ Future Improvements (Suggestions)
- **Time-series trends** (YoY/MoM), forecasting  
- **Engagement metrics** (likes, comments, shares)  
- **Category-wise** breakdown (music, news, entertainment, etc.)  
- **Geo-analysis** (country/region maps)  
- **RLS** (Row-Level Security) for user-specific views

## 🙌 Credits
Dashboard design & implementation: **Roshan Kumar**  
Inspiration/Reference: Open-source YouTube analytics dashboards

## 📄 License
MIT (ya jis license ka aap use karein).
