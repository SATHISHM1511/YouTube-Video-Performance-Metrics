# YouTube-Video-Performance-Metrics

### **README: YouTube Video Performance Metrics Analysis**  

#### **Project Overview**  
This project analyzes YouTube video performance metrics, focusing on key engagement indicators such as views, likes, and shares. By handling missing values, summarizing statistical insights, and visualizing trends, the analysis helps content creators and marketers understand audience engagement patterns and optimize content strategies.  

#### **Features & Analysis**  
- **Data Preprocessing:** Handles missing values for video tags.  
- **Engagement Rate Calculation:** Computes the ratio of (likes + shares) to views.  
- **Statistical Summary:** Provides the average number of likes per video.  
- **Data Aggregation:** Calculates total views per category.  
- **Performance Metric Analysis:** Computes the likes-to-views ratio.  
- **Trend Visualization:** Generates separate line charts for views, likes, and shares over time.  

#### **Requirements**  
Ensure you have the following Python libraries installed before running the script:  
```bash
pip install pandas matplotlib seaborn
```  

#### **How to Run the Script**  
1. Place the dataset (`youtube_video_metrics_large.csv`) in the same directory as the script.  
2. Run the script using:  
   ```bash
   python script_name.py
   ```
3. The output will include statistical summaries and three separate graphs displaying trends in views, likes, and shares.  

#### **Expected Output**  
- Printed insights, including the average likes per video and total views per category.  
- Three line charts showing how views, likes, and shares fluctuate over time.  

#### **Conclusion**  
This project helps content creators and digital marketers analyze video performance, optimize content strategies, and improve audience engagement based on data-driven insights. 
