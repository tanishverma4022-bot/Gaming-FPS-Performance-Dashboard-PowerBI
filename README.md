# Gaming-FPS-Performance-Dashboard-PowerBI
Power BI dashboard analyzing gaming FPS performance across 22 GPUs, 11 CPUs, 30 games &amp; 3 resolutions.
A Power BI capstone project analyzing gaming benchmark data across 22 GPU models, 11 CPU models, 30 games, and 3 resolutions, with a highest recorded FPS of 501.

📌 Problem Statement

Gamers and hardware sellers struggle to answer:

Which GPU/CPU gives the best FPS for a given budget?
How do NVIDIA, AMD, and Intel actually compare?
How much does ray tracing hurt performance?
Which games are most demanding on hardware?
Which hardware combos reliably hit 100+ FPS?

🧹 Data Cleaning
Removed duplicate benchmark entries
Filled/handled missing FPS and benchmark scores
Standardized GPU/CPU naming (e.g. "RTX4070Ti" vs "RTX 4070 Ti")
Unified resolution formats ("1920x1080" vs "1080p")
Converted RAM/VRAM text columns to numeric
Cleaned unrealistic outlier scores
Created a custom "100+ FPS" category column

📊 Key Insights
NVIDIA leads GPU market share (>50%) and average FPS; AMD is 2nd, Intel 3rd
Ray tracing drops average FPS from ~130 → ~100
1080p remains the most-used resolution (39%), followed by 1440p, then 4K
16GB RAM is the most common gamer configuration
Higher VRAM correlates with higher average FPS
100+ FPS is achievable on many budget builds (e.g., Core i3-12100) with balanced RAM/GPU
🛠️ Tools Used

Power BI · Power Query · DAX

📁 Dashboard Pages
Overview (KPIs + Slicers)
FPS by GPU Model
Resolution Comparison
Ray Tracing Impact
Brand Comparison
GPU Market Share
RAM Preference
Game Engine & Benchmark Comparison
Best Hardware (100+ FPS) Table
