Welcome to my Exploratory Data Analysis (EDA) project!

I built this pipeline to dive deep into raw user data and see what kind of hidden stories I could uncover. Instead of just working with a clean, pre-packaged CSV, I wanted to simulate a real-world scenario. So, I wrote a Python script to fetch live data directly from a RESTful API, carefully handling pagination so I didn't miss a single user.

Of course, real-world data is rarely neat! A big part of the challenge was wrangling deeply nested JSON responses, like digging out specific cities and countries buried inside complex address dictionaries. Once I flattened all that out, I rolled up my sleeves to clean the dataset, dynamically filling in missing values and fixing data types so everything was perfectly prepped for analysis.

Then came the fun part: bringing the numbers to life! I used Pandas, Matplotlib, and Seaborn to design a collection of 14 custom visualizations. From vibrant correlation heatmaps to side-by-side bar charts, these graphs make it super easy to understand user demographics, physical traits, and geographic trends at a glance.

Feel free to explore the code, check out the data visualizations below, and see what the data has to say!

Built With: Python | Pandas | Seaborn | Matplotlib | Requests

Data Visualizations Gallery
Here is a look at the 14 charts generated during the analysis!

![1](https://github.com/user-attachments/assets/0028787b-ccec-49ec-b4e6-6fe50a53d07f)
![2](https://github.com/user-attachments/assets/8ab5ae9e-eb2c-4c93-8b22-24ab64e3100d)
![3](https://github.com/user-attachments/assets/f8ad29f8-aaf3-468c-a311-a82bf88c649e)
![4](https://github.com/user-attachments/assets/70deec98-6e2b-4c5f-9d12-d1880ba85a03)
![5](https://github.com/user-attachments/assets/1b3238ab-01b9-4dfb-9492-8510d17be759)
![6](https://github.com/user-attachments/assets/84005079-ac2b-4234-9cb2-c635284915ba)
![7](https://github.com/user-attachments/assets/93526166-a3a8-4269-a37d-3ccd2423abaa)
![8](https://github.com/user-attachments/assets/03e6ce8b-e21d-4153-936c-0c002078813b)
![9](https://github.com/user-attachments/assets/5973c58f-a3a7-4af3-9fc9-f69517dfe6d8)
![10](https://github.com/user-attachments/assets/0b04fca1-8973-4ba9-ae4c-4576971e6333)
![11](https://github.com/user-attachments/assets/3a573886-c769-4b29-b39d-ad6cdb4d53c0)
![12](https://github.com/user-attachments/assets/377ea43d-0073-4656-88bc-5bd11ed39533)
![13](https://github.com/user-attachments/assets/31454216-8439-487d-b125-2484dc323d0a)
![14](https://github.com/user-attachments/assets/ee348621-d833-4801-b733-1619cb21bb05)
