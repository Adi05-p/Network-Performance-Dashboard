# 🌐 Network Performance Dashboard

## 🏢 Project Context
This dashboard analyzes the network performance of **NetCloud Global**, a simulated cloud infrastructure company operating four regional data centers (East, West, North, South).  
The goal is to monitor and improve **speed, reliability, and bandwidth utilization** using Power BI.

---

## 🎯 Objective
To visualize and analyze key network performance indicators (KPIs) — helping identify underperforming regions or overloaded devices, and supporting data-driven network optimization.

**Key Metrics:**
- 🕒 **Latency (ms):** Measures network speed  
- 📉 **Packet Loss (%):** Measures data reliability  
- 📶 **Bandwidth (MBps):** Measures load distribution  

---

## ⚙️ Tools Used
- **Power BI** – Data visualization and KPI dashboard  
- **Excel / CSV** – Dataset source  
- **Python** – Synthetic data generation for realistic network metrics  

---

## 🧾 Dataset
- **10 devices**, across **4 regions** (East, West, North, South)  
- **Daily data** recorded over **7 days**  
- **Columns:**
  - Timestamp  
  - Device_ID  
  - Region  
  - Latency_ms  
  - Packet_Loss_%  
  - Bandwidth_MBps  
  - Uptime_%  

---

## 📊 Dashboard Visuals

### 1️⃣ Average Latency by Region (Line Chart)
Tracks daily network speed trends across regions.  
> Shows how latency fluctuates over time — South and West regions experience occasional spikes, indicating peak-hour congestion.

### 2️⃣ Packet Loss by Region (Bar Chart + Gradient)
Compares data transmission reliability.  
> Green regions = stable connection, Red = high packet loss. South region shows the highest instability (~2%).

### 3️⃣ Bandwidth Usage by Device (Column Chart + Gradient)
Identifies heavily loaded devices vs. underused ones.  
> Device_3 and Device_7 have the highest bandwidth usage (~17 MBps), suggesting a need for load balancing.

### 4️⃣ KPI Summary Cards
| Metric | Average Value | Interpretation |
|---------|----------------|----------------|
| Latency | ~68 ms | Good speed |
| Packet Loss | 0.9% | Minor transmission issues |
| Bandwidth | 12 MBps | Moderate usage |

---

## 💡 Key Insights
- 🌍 **South region** has slightly higher latency and packet loss, requiring investigation.  
- ⚙️ **Device_3** and **Device_7** show heavy network load — redistribute bandwidth.  

---

## 🧠 Learning Outcomes
- Built a **Power BI dashboard** from scratch with interactive visuals and KPI metrics.  
- Applied **conditional formatting** for intuitive performance insights.  
- Gained hands-on experience in **data storytelling and visualization** for business analytics.  

---

## 🚀 Business Impact
This dashboard helps network teams:
- Identify regional performance bottlenecks  
- Optimize resource distribution  
- Maintain SLA compliance and improve user experience  

---

**👩‍💻 Author:** [Adetee Paatil](https://github.com/Adi05-p)  
**📅 Date:** November 2025  
**🏷️ Tags:** Power BI · Business Analytics · Data Visualization · Network Performance · Dashboard Design
