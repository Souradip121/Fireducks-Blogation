

# 🦆 **FireDucks vs GeoPandas: Geospatial Performance Showdown**  

## 📌 **Introduction**  
This project benchmarks the performance of **FireDucks** and **GeoPandas** for geospatial data processing using a shapefile of Indian states.  
We compare the libraries in terms of:  
- 🕰 **Execution Time**  
- 🧠 **Memory Usage**  

---

## 🛠 **Prerequisites**  

Ensure you have Python installed (Python 3.8 or later recommended).  
Install the necessary dependencies using the provided `requirements.txt` file:  

```bash
pip install -r code/requirements.txt
```

---

## 📂 **Folder Structure**  
```bash
.
├── code
│   ├── requirements.txt      # Dependencies
│   ├── test.ipynb             # Jupyter Notebook for Benchmarking
├── data
│   └── india_st.shp           # Shapefile for Geospatial Analysis
├── README.md                  # Project Documentation
```

---

## 🚀 **How to Run the Code**  

1. Clone the repository:  
```bash
git clone https://github.com/your-repo-url.git
cd your-repo-folder
```

2. Install dependencies:  
```bash
pip install -r code/requirements.txt
```

3. Open the Jupyter notebook:  
```bash
jupyter notebook code/test.ipynb
```

4. Follow the notebook steps to:  
- Load the shapefile using **GeoPandas**  
- Convert it into a **FireDucks** DataFrame  
- Perform spatial filtering using a bounding box  
- Benchmark execution time and memory consumption  

---

## 📊 **Results Interpretation**  

- **Execution Time**: Lower times indicate faster performance.  
- **Memory Usage**: Lower memory consumption is ideal for large datasets.  

---

## 💡 **Conclusion**  

- **FireDucks** provides faster initial runs and consumes less memory.  
- **GeoPandas** benefits from internal caching, making it efficient for repeated operations.  
- Choose **FireDucks** for memory-intensive tasks and **GeoPandas** for feature-rich analysis.  

---

## 🛎 **Contributing**  

Feel free to contribute by raising issues or submitting pull requests!  

---

## 📝 **License**  

This project is licensed under the **MIT License**.