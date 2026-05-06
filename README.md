MongoDB Task 2 – Advanced Queries
📌 Objective
To perform advanced MongoDB queries using mongosh.

🛠 Tools Used
MongoDB
Mongosh
Windows PowerShell
📚 Operations Performed
Sorting documents
Limiting results
Filtering using conditions
Regex search (MongoDB / NoSQL)
🔍 Sample Queries
Top 3 Recent Books
db.books.find().sort({ published_year: -1 }).limit(3)

MongoDB Books
db.books.find({ title: { $regex: "MongoDB", $options: "i" } })

NoSQL Books
db.books.find({ title: { $regex: "NoSQL", $options: "i" } })

✅ Conclusion
Successfully executed advanced MongoDB queries including sorting, filtering, and pattern matching.
