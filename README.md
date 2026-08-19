# 📊 Facebook Thailand — EDA

An Exploratory Data Analysis project on Facebook posts from Thailand to understand content performance, user engagement, and the best time to post.

---

## 🎯 Objective
Analyze different types of Facebook posts.
Understand user engagement through reactions, comments, shares, and likes.
Identify the best-performing status_type.
Analyze engagement based on hour, day, and year.
Identify patterns in viral posts.

---

## 🛠️ Tools Used
Python
Pandas
NumPy
Matplotlib
Seaborn

---

## 🔍 Data Cleaning
Checked for missing values.
Removed 4 completely blank columns.
Removed 53 duplicate posts using status_id.
Converted status_published into datetime format.
Extracted hour, day, year, and month from the publishing date.

---

## ⚙️ Feature Engineering

Created a new engagement feature by combining:

Likes + Comments + Shares + Reactions

This helped compare the overall performance of different post types.

---

## 📈 EDA & Key Insights
Photos are the most frequently posted content.
Videos can achieve higher typical engagement, although their performance is less consistent.
Some videos become highly viral, creating significant outliers.
Engagement varies depending on the posting time.
10 AM has the highest average engagement according to the analysis.
Viral engagement spikes were particularly noticeable on Wednesdays and Mondays.
Reactions, comments, shares, and likes show strong relationships with overall engagement.

---

## 📌 Conclusion

The analysis shows clear patterns in Facebook engagement. Photos are widely used and perform well, while videos have stronger potential for high engagement and viral performance. Posting time also plays an important role, with 10 AM showing the highest average engagement in this dataset.

Overall, combining the right content type with an appropriate posting time can help improve Facebook engagement.
