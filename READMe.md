# Cloud-Based Pharmacy Inventory and Medicine Expiry Monitoring System

## 1. Project Description

The Cloud-Based Pharmacy Inventory and Medicine Expiry Monitoring System is designed to simplify pharmacy operations through automated inventory management and smart medicine identification.

The system allows users to manage medicines, suppliers, batches, stock quantities, purchase and sales transactions, and medicine expiry dates.

An important feature of this project is **Smart Medicine Recognition**. Users can capture or upload a medicine package image or scan its barcode to identify the medicine and retrieve available information automatically.

Using Optical Character Recognition (OCR), barcode scanning, and medicine database lookup, the system extracts available details such as:

- Medicine name
- Brand name
- Generic name
- Manufacturer
- Composition and strength
- Batch number
- Manufacturing date
- Expiry date
- Maximum Retail Price (MRP)

The extracted information is automatically filled into the respective forms. Users can verify and correct the information before saving it.

The system also generates alerts for expired medicines, medicines nearing expiry, and low-stock products. It aims to reduce manual work, prevent medicine wastage, and improve pharmacy inventory accuracy.

## 2. Key Features

1. **Smart Medicine Recognition:** Identify medicines using photographs and barcodes.
2. **Automatic Information Extraction:** Extract medicine details using OCR and database lookup.
3. **Medicine Management:** Add and maintain medicine records.
4. **Batch Management:** Maintain batch numbers, quantities, and expiry dates.
5. **Supplier Management:** Store supplier information.
6. **Stock Management:** Record stock IN and OUT transactions.
7. **Expiry Monitoring:** Identify expired and near-expiry medicines.
8. **Low-Stock Alerts:** Generate alerts when stock falls below the reorder level.
9. **Dashboard:** Display inventory statistics and alerts.
10. **Cloud Deployment:** Deploy the application using AWS services.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Flask | Backend framework |
| HTML, CSS, Bootstrap | Frontend development |
| JavaScript | Camera and barcode scanning |
| EasyOCR | Text extraction from medicine images |
| OpenCV | Image processing |
| MySQL | Database management |
| Docker | Application containerization |
| AWS EC2 | Application hosting |
| Amazon RDS | Cloud database |
| Amazon ECR | Docker image storage |
| Amazon VPC | Secure networking |
| Application Load Balancer | Traffic distribution |
| EC2 Auto Scaling | Application scalability |
| Amazon CloudWatch | Monitoring and logging |
| AWS IAM | Access management |

## 4. Project Architecture

The application follows this workflow:

1. User captures a medicine image or scans its barcode.
2. The system extracts information using OCR and barcode recognition.
3. Additional medicine information is retrieved through database lookup.
4. Extracted information is displayed for verification.
5. Verified medicine and batch details are stored in MySQL.
6. The inventory system monitors stock quantities and expiry dates.
7. Alerts are generated for low-stock, near-expiry, and expired medicines.
8. The application is deployed and monitored using AWS services.

## 5. Team Members

**Team Number:** 12  
**Section:** 3

| Name | Student ID |
|---|---|
| K. Vansika | 2520030527 |
| B. Nikita | 2520030172 |

## 6. Project Guide

**Guide Name:** Dr. S. Vinay Kumar  
**Designation:** Assistant Professor  
**Department:** Computer Science and Engineering

## 7. Course Details

- **Course:** Cloud Infrastructure and Services
- **Course Code:** 25CS2206E
- **Academic Year:** 2026–2027

## 8. Expected Outcome

The project aims to develop a smart and scalable pharmacy inventory management solution that:

- Reduces manual medicine data entry.
- Automatically identifies medicines using images and barcodes.
- Improves inventory accuracy.
- Tracks medicine batches and expiry dates.
- Reduces medicine wastage.
- Prevents stock shortages.
- Provides centralized cloud-based inventory management.

## 9. Future Enhancements

- Improved medicine database integration.
- More accurate medicine recognition.
- Automated inventory reports.
- Advanced analytics and notifications.
- Enhanced security and user authentication.

---

**Project:** Cloud-Based Pharmacy Inventory and Medicine Expiry Monitoring System  
**Team:** 12  
**Academic Year:** 2026–2027
