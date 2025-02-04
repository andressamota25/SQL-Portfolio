# 🎨 SQL Artwork Analysis - Hokusai & Hiroshige  

This project analyzes **72 woodblock prints** created by Japanese artists **Katsushika Hokusai** and **Utagawa Hiroshige**. The prints include famous works such as *The Great Wave off Kanagawa*. Using SQL, I explored computational image analysis metrics like brightness, contrast, and entropy.  

---

## 🖼️ **Dataset Overview**
The database `views.db` contains details on:  
- **Title** of the print  
- **Artist** (Hokusai or Hiroshige)  
- **Average color** (computed digitally)  
- **Brightness** (light intensity)  
- **Contrast** (difference between light/dark areas)  
- **Entropy** (measure of randomness in the image)  

---

## 🔍 **SQL Queries & Insights**
| Query | Description |
|-----------------|------------|
| `most_bright.sql` | Finds the brightest artwork in the dataset. |
| `highest_contrast.sql` | Determines which print has the highest contrast. |
| `artist_comparison.sql` | Compares average brightness & contrast between Hokusai and Hiroshige. |
| `entropy_ranking.sql` | Ranks prints by entropy to analyze complexity. |

---

## 🛠️ **SQL Techniques Used**
✅ **Filtering Data** with `WHERE`  
✅ **Sorting & Ranking** with `ORDER BY`  
✅ **Aggregating Data** with `AVG()`, `MAX()`, `COUNT()`  
✅ **Comparing Artists** with `GROUP BY`  
✅ **Subqueries** for advanced insights  

---

## 🚀 **How to Run**
1. Download `views.db` (not included in this repo due to file size).  
2. Open SQLite and load the database:
   ```sql
   sqlite3 views.db
