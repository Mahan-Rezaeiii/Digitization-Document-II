# **Digitization Document II via Tabula-Py (Winter 2024)**

This repository contains a sample of my work as a Research Assistant to **[Dr. Sepehr Ekbatani](https://sepehrekbatani.com/)** and **[Dr. Sahber Ahmadi-Renani](https://sites.google.com/view/ahmadirenani/home)** at the Department of Economics at the [Tehran Institute for Advanced Studies (TeIAS)](https://teias.institute/).

---

## **Overview**

This project includes a section of a working paper titled *"Geography of Higher Education Opportunity and the Role of Place-Based Policies,"* authored by **[S. Ahmadi-Renani](https://sites.google.com/view/ahmadirenani/home)** and **[S. Ekbatani](https://sepehrekbatani.com/)**. (Draft not available)

As a research assistant, I digitized administrative PDF reports published by Iran’s National Organization of Educational Testing (`NOET`) containing detailed results of the national university entrance exam (Konkour) for all provinces over the period 2015-2023. This is the first time this data has been digitized for our research. The data provides insights into the demand side of Iran's higher education system and is classified at the district level. (It is important to note that there are nearly 1,040 districts in Iran.)

This data includes the following features:

- Number of registered students by gender, major, and district.
- Number of participated students by gender, major, and district.
- Number of Admitted students by gender, major, and district.
- Average GPA of students by gender, major, and district.
- Average percentage scores for each course in exam.
- ...

---

## **From PDF to Dataset**

In this project, I used the *"Tabula-Py"* library for the digitization process. This library is specifically designed to extract tables from PDFs, making it suitable for **`Machine-Readable`** documents. It relies on **`Coordinates`** within the PDF to perform the digitization. This library works best with structured, table-rich documents.

In my code folder, I provided explanations for each step I took to digitize a sample document and convert it into a well-structured DataFrame in CSV format.

---

## **Contact**

If you have any questions or feedback, feel free to reach out via email: mahanrezaee98@gmail.com.