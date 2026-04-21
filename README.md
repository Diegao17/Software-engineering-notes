# Data Engineering Learning Journey 🚀

This repository reflects my learning process throughout the semester while working with modern data pipelines, AWS tools, and basic search engine concepts.

Instead of only documenting what I did, this focuses on what I understood and learned from each lab.

---

## 🧱 Modern Data Pipeline Architectures

### What I Learned

Through this topic, I understood how modern systems handle large amounts of data efficiently using cloud-based solutions.

One of the most important things I learned is the difference between **ETL and ELT**:

* ETL transforms data before storing it
* ELT stores raw data first and transforms it later

This helped me understand why modern tools prefer ELT — it is more flexible and scalable.

I also learned the difference between:

* **Data Lakes** → store raw, unprocessed data
* **Data Warehouses** → store clean, structured data ready for analysis

Another key concept was **serverless architecture**, which means I don’t need to manage servers. Tools like Athena and Glue handle everything automatically, which makes development faster and easier.

Finally, I understood the difference between:

* Batch processing (data in chunks)
* Real-time processing (data instantly)

This gave me a clearer idea of how real-world systems like Netflix or Uber process data.

---

## 🔍 Lab 1.1 – AWS Athena

### What I Learned

In this lab, I learned how to query data directly from Amazon S3 using SQL without needing a database server.

At first, I thought Athena was just another database, but I realized:

* It doesn’t store data
* It only queries data stored in S3

This helped me understand how powerful serverless querying is.

I also learned the importance of:

* Structuring data properly
* Using schemas from AWS Glue
* Writing efficient SQL queries

One important insight was that Athena charges based on how much data you scan.
So optimization matters a lot.

### Key Takeaways

* You can analyze big data without infrastructure
* SQL is still very important in cloud environments
* Poor queries = higher cost

---

## 🔄 Lab 1.2 – AWS Glue (ETL)

### What I Learned

This lab helped me understand how ETL processes actually work in a real environment.

Before this, ETL was just theory. With Glue, I saw how:

* Data is extracted from S3
* Transformed using PySpark
* Loaded into another storage or table

One of the most interesting parts was the **crawler**, which automatically detects the schema. That made me realize how automation reduces manual work in data engineering.

I also learned that:

* Glue uses distributed processing (big data concept)
* Jobs can scale depending on the data size

### Key Takeaways

* ETL is essential for preparing data
* Automation (like crawlers) saves time
* Understanding data transformation is more important than just running jobs

---

## 🌐 Lab 2.1 – Mini Web Search Engine

### What I Learned

This lab helped me understand how search engines actually work behind the scenes.

Before this, I only thought about typing and getting results, but now I understand the components:

* **Crawler** → collects data
* **Indexer** → organizes data
* **Search function** → finds matches

The most important thing I learned is that:

* Searching is not simple
* It depends heavily on how data is stored and indexed

Even with a basic implementation, I could see that:

* Efficiency matters a lot
* Ranking results is complex

### Key Takeaways

* Data structures are critical in search systems
* Indexing makes searching faster
* Real search engines are much more complex than they seem

---

## 💡 Overall Reflection

Throughout this semester, I moved from understanding concepts in theory to actually applying them using real tools.

What I improved the most:

* Understanding how cloud data tools work together
* Writing better and more efficient queries
* Seeing how data flows from raw to processed
* Thinking more like a data engineer instead of just a programmer

This repository represents not only what I did, but how my understanding evolved over time.

---
