# QR-code-based-Excel-Attendace
* Developed QR code attendance system using Python, harnessing the power of Tkinter, NumPy, OpenCV, and QR code generation libraries to create an efficient and user-friendly solution.
* Efficiently records and manages attendee participation through QR code data, serving as attendance tracking mechanism.

## How to generate QR code?

- In the `QR Codes` folder

1. Update the data base in file `Data_base.txt`. Make sure each students name resides in a new line without any space.  
!![data_base](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/aad3e702-af7d-44b1-8ce8-791d0d9eadc6)

2. Run the `Generate_QR.py` file by double clicking on it.  
![Generate_QR](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/d1d89b3d-da20-4959-9a43-eadffae429ce)  

3. Required QR code for the data base will be created.  
![QR_code](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/d21c4d8e-f6f1-4f3d-acd1-577e2ddbda1b) 

## How to take Attendace?

To Take attendace run the `QR_Attendance.py` file by double clicking on it.  

![take_attendance](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/93fc8b68-a6a3-4697-9118-f2b29303fe25) 

A GUI will pop up. Fill in the details to set the Attandace sytem for your class.  

![GUI](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/48bb3fe7-16c9-4a1d-b43f-c6c39b6892d0)

Once the information is filled, checkout the box and click `Ready to Scan QR`. This will open up the terminal for conformation and camera to scan the QR. 

![QR_scan](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/5fef69d6-37db-46c2-9aa9-88b30df86c1d)  

![QR_scan](./Reference/QR_scan.jpg)

You will recive the conformation on terminal on successful scan.

Once everyone has scanned their QR, press `q` to quit the process. This will close the camera and save the attendance record in `.xls` format.

![xl](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/ef4b219b-20ad-49eb-827c-f6db3e63e855)

At the end this excel sheet is mailed to respective teacher in encoded format.

![mail](./Reference/mail.jpg)

## How to Decode the Excel sheet ?
To decode the excel sheet , just download the file and save it with `.xls` extension.

![save](https://github.com/AkshitNarang/Attendance-Project/assets/67042530/d9d0c807-e893-403d-838f-85f1b4193e58)
