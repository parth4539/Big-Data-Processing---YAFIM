# Big-Data-Processing

# 🔍 YAFIM: Yet Another Frequent Itemset Mining Algorithm Using Spark

This project implements a parallel version of the **Apriori algorithm** for **frequent itemset mining** using **PySpark** and the **RDD API**. It is optimized for distributed processing of large transactional datasets, demonstrated using the classic **Mushroom dataset**.

---

## 📌 Project Highlights

- ✅ Parallelized Apriori algorithm using **Apache Spark (PySpark)**
- ✅ Works on any transactional dataset (e.g., market basket data)
- ✅ Evaluates runtime across different numbers of Spark cores (1, 2, 3)
- ✅ Executed on **Google Colab** with integration to **Google Drive**

---

## ⚙️ Technologies Used

- Python
- Apache Spark (PySpark)
- Google Colab
- Google Drive (for dataset)
- Mushroom dataset (UCI repository)

---

## 🚀 How to Run (Google Colab)

1. **Upload Dataset**  
   - Place `mushroom.dat` inside your Google Drive (e.g., `/MyDrive/Big data/mushroom.dat`).

2. **Open Notebook**  
   Open `YAFIM_Colab.ipynb` in Google Colab.

3. **Install Spark**  
   ```python
   !pip install --quiet pyspark

