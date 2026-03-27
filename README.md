# Google Cloud Storage: Qwik Start – Console Lab

This repository documents my hands-on work completing the Google Cloud Storage: Qwik Start lab using the Google Cloud Console. The lab walks through the fundamentals of object storage on Google Cloud, including bucket creation, object uploads, folder organization, and public access configuration.

---

## 🚀 Lab Objectives

In this lab, I practiced how to:

- Create a Cloud Storage bucket using the Google Cloud Console  
- Upload objects (files) into a bucket  
- Organize objects using folders and subfolders  
- Configure public access for objects  
- Delete buckets and understand lifecycle behavior  

---

## 🧰 Technologies Used

- Google Cloud Platform (GCP)
- Cloud Storage (GCS)
- Google Cloud Console (UI)
- Temporary student credentials provided by Google Skills Boost

---

## 📌 Steps Completed

### 1. Created a Cloud Storage Bucket
- Navigated to Cloud Storage → Buckets
- Created a bucket using the project ID as the globally unique name  
- Chose:
  - Location type: Region  
  - Storage class: Standard  
  - Access control: Uniform  
- Disabled *public access prevention* to allow object sharing

---

### 2. Uploaded an Object
- Downloaded the provided `kitten.png` image  
- Uploaded it into the bucket using Upload → Upload files  
- Verified metadata such as size and MIME type  

---

### 3. Made the Object Public
- Opened the Permissions tab  
- Granted `allUsers` the Storage Object Viewer role  
- Confirmed public access  
- Copied the public URL:

---



### 4. Created Folders and Subfolders
- Created `folder1/`  
- Inside it, created `folder2/`  
- Uploaded a screenshot into the subfolder  

---

### 5. Deleted a Folder and File
- Returned to the objects list  
- Selected the folder and file and clicked **Delete**  
- Typed `DELETE` to confirm
  

---

## 📝 Key Concepts Reinforced

| Concept | Summary |
|--------|---------|
| **Buckets** | Globally unique containers for objects |
| **Objects** | Files stored in Cloud Storage; names must be unique *within a bucket* |
| **Public Access** | Controlled via IAM roles such as `Storage Object Viewer` |
| **Folder Structure** | Logical organization; GCS is technically flat but simulates folders |
| **Uniform Access Control** | Permissions applied at the bucket level |
