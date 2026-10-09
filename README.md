# 🔵 K-Means Clustering Visualization

**English | فارسی**

## 🇬🇧 English

A beginner-friendly **Machine Learning** project that demonstrates the **K-Means clustering** algorithm using synthetic data.

The notebook generates 400 two-dimensional data points grouped around four centers, applies K-Means with four clusters, and visualizes the assigned clusters and their centroids. It also compares the generated labels with the cluster assignments found by the model.

### 🎯 Project Goals

- Generate a simple synthetic dataset with `make_blobs`.
- Visualize the data points.
- Fit a K-Means model with four clusters.
- Predict a cluster assignment for each point.
- Plot the predicted clusters and cluster centroids.
- Compare the original generated labels with the model's clusters visually.

### 🧰 Technologies

- Python
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### ▶️ How to Run

1. Install the required libraries:

   ```bash
   pip install numpy matplotlib seaborn scikit-learn jupyter
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `kmeans-clustering-visualization.ipynb` and run the cells in order.

### 📁 Project Structure

```text
kmeans-clustering-visualization/
├── README.md
└── kmeans-clustering-visualization.ipynb
```

### 📝 Notes

- The dataset is generated inside the notebook, so a separate CSV file is not required.
- K-Means cluster IDs are arbitrary. For example, cluster `0` does not necessarily correspond to original label `0`; the important part is the grouping, not the numeric label itself.
- This is a learning project intended to practice the basics of unsupervised machine learning and data visualization.

---

## 🇮🇷 فارسی

این یک پروژه‌ی آموزشی و مبتدی در زمینه‌ی **یادگیری ماشین** است که الگوریتم **خوشه‌بندی K-Means** را با استفاده از داده‌های مصنوعی نشان می‌دهد.

در این Notebook، تعداد ۴۰۰ نقطه‌ی دوبعدی پیرامون چهار مرکز تولید می‌شود. سپس مدل K-Means با چهار خوشه آموزش داده می‌شود و نتیجه‌ی خوشه‌بندی به همراه مرکز هر خوشه روی نمودار نمایش داده می‌شود. در انتها، برچسب‌های اولیه‌ی داده‌های تولیدشده نیز به‌صورت تصویری با نتیجه‌ی مدل مقایسه می‌شوند.

### 🎯 اهداف پروژه

- تولید یک دیتاست ساده با استفاده از `make_blobs`
- نمایش نقاط داده روی نمودار
- آموزش مدل K-Means با چهار خوشه
- پیش‌بینی خوشه‌ی مربوط به هر نقطه
- نمایش خوشه‌های پیش‌بینی‌شده و مراکز آن‌ها
- مقایسه‌ی تصویری برچسب‌های اولیه با خروجی مدل

### 🧰 ابزارها و کتابخانه‌ها

- Python
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### ▶️ نحوه‌ی اجرا

۱. کتابخانه‌های موردنیاز را نصب کنید:

```bash
pip install numpy matplotlib seaborn scikit-learn jupyter
```

۲. محیط Jupyter Notebook را اجرا کنید:

```bash
jupyter notebook
```

۳. فایل `kmeans-clustering-visualization.ipynb` را باز کنید و سلول‌ها را به‌ترتیب اجرا کنید.

### 📁 ساختار پروژه

```text
kmeans-clustering-visualization/
├── README.md
└── kmeans-clustering-visualization.ipynb
```

### 📝 نکات

- دیتاست داخل خود Notebook تولید می‌شود؛ بنابراین به فایل CSV جداگانه نیاز نیست.
- شماره‌ی خوشه‌ها در K-Means معنای ثابتی ندارد. برای مثال، خوشه‌ی شماره‌ی `0` الزاماً با برچسب اولیه‌ی `0` یکسان نیست؛ مهم، گروه‌بندی نقاط است نه شماره‌ی خوشه.
- این پروژه برای تمرین مفاهیم پایه‌ی یادگیری ماشین بدون نظارت (Unsupervised Learning) و مصورسازی داده‌ها ساخته شده است.

---

## 👩‍💻 Author | نویسنده

**Fatemeh Rahimi**

Beginner AI & Machine Learning Developer 🌱

If you find this project useful, feel free to ⭐ the repository.
اگر این پروژه برایتان مفید بود، می‌توانید به مخزن آن ⭐ بدهید.
