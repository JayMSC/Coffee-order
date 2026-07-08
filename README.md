
# ☕ Coffee Order App

## 📌 Introduction
The Coffee Order App is a business application developed using Microsoft Power Apps. It allows users to browse coffee items, place orders, and manage customer requests through an easy-to-use interface. The application demonstrates low-code development using the Microsoft Power Platform while integrating cloud-based data storage and automation.

---

## 🚀 Features

- ☕ Browse available coffee items
- 🛒 Place coffee orders
- 👤 Customer information management
- 📋 Order history
- 🔍 Search and filter coffee items
- 📱 Responsive Canvas App design
- ☁️ Cloud-based data storage using SharePoint
- Based of (Curd Oprations)
---

## 🛠️ Technologies Used

- Microsoft Power Apps (Canvas App)
- Power Fx
- SharePoint 


## 📷 Application Screens

 1.Code of (First Screen) in gallery Data:
[SortByColumns(Filter([@'Coffee Bevrages'], StartsWith(Title, TextSearchBox1.Text)), "Title", If(SortDescending1, SortOrder.Descending, SortOrder.Ascending)) ]

 the data will be stored the data and display in search box
 
<img width="1511" height="765" alt="image" src="https://github.com/user-attachments/assets/088292b0-78b4-4263-a2b5-bf137863d38a" />

a) the Code of Plus icon of Adding data
[NewForm(EditForm1);Navigate(EditScreen1, ScreenTransition.None)]

This will be get added data

<img width="1407" height="852" alt="image" src="https://github.com/user-attachments/assets/b005043b-a6bf-4670-89f8-89187ce83133" />

b)  The code of the First set that dislay the data by writing name By [StartsWith(Title, TextSearchBox1.Text)) ]

 this will be search by name
 
<img width="1352" height="777" alt="image" src="https://github.com/user-attachments/assets/a4490957-1794-481e-b171-2d1d4bfde153" />

c) Refresh the data using referesh icon
      By Code using : Refresh([@'Coffee Bevrages']) Data
      
<img width="1377" height="755" alt="image" src="https://github.com/user-attachments/assets/d075444f-6869-4276-96f3-02695c0c58a8" />

 d) Short up data by Accending and Decending order
 Code:UpdateContext({SortDescending1: !SortDescending1})

<img width="1372" height="807" alt="image" src="https://github.com/user-attachments/assets/869e51c1-4166-4831-80d5-2a5f39420c83" />

 
 2.Code of (Second Screen) the detail Screen Data:
 if i click on the first screen will navigate to Detail Screen and show the data if detail screen By (Item Galerry.Selected)

<img width="1221" height="717" alt="image" src="https://github.com/user-attachments/assets/5e30c9b4-5987-4cd3-af75-0ce6de54ae1a" />

a) In the edit section  the edit icon will go to edit 
the code will be  (EditForm(EditForm1);Navigate(EditScreen1, ScreenTransition.None);)

<img width="1367" height="808" alt="image" src="https://github.com/user-attachments/assets/62bab81c-ccbd-46e7-9206-34308a678ca0" />

and the the form will display will click on edit 

<img width="311" height="527" alt="image" src="https://github.com/user-attachments/assets/f7bd471b-07a9-48fe-80f8-bbdb3c28590b" />

after the forms get display will have( Pop Up message)

<img width="323" height="557" alt="image" src="https://github.com/user-attachments/assets/9c6bb5ae-e013-49ab-a8ca-a23bf4cb2180" />



       in this  Button will this Code :Back(); and yes button will Submit form(Form1)

 b) in the delete section the data get deleted when bin button get click 

 <img width="1096" height="808" alt="image" src="https://github.com/user-attachments/assets/22ab1b77-93f5-4306-b5fa-7c57ce2adb00" />

  and this pop up message will  come over the data

  the code of no will tun Code: Back(); in no Button and Yes button Code : Remove([@'Coffee Bevrages'], BrowseGallery1.Selected); If (IsEmpty(Errors([@'Coffee Bevrages'], BrowseGallery1.Selected)), Back());
  
 <img width="1835" height="743" alt="image" src="https://github.com/user-attachments/assets/6d4db419-5352-4cbc-8423-a253142b36c2" />

 
 ---

## 🎥 Demo Video

You can watch the application demo below.

[C:\Users\Jayshree\Downloads\Jayshree Tapase\images\Project.mp4](https://github.com/user-attachments/assets/6c33a7a3-fbb3-438f-ba05-5d6989fbc6ef
)


---

## ⚙️ How to Use

1. Open the Power Apps application.
2. Select your preferred coffee.
3. Enter customer details.
4. Place the order.
5. View order confirmation.

---

## 🎯 Purpose

This project was developed to demonstrate practical experience with Microsoft Power Apps and business application development using the Microsoft Power Platform.

---

## 👩‍💻 Developed By

**Jayshree Tapase**

LinkedIn:[ Your LinkedIn Profile](https://www.linkedin.com/in/jayshree-tapase-488534326/)
