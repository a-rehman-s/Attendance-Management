# Attendance Management System  

## Project Overview  
The Attendance Management System is a **Java-based desktop application** developed to streamline the process of tracking student attendance in hostels or educational institutions. It features a user-friendly interface for administrators and students to view, manage, and update attendance records effectively. The system employs **Java Swing** for the graphical user interface and **CSV handling** for data operations.  

---

## Features  

### Admin Login  
- Secure login access restricted to administrators.  

### Home Page  
- Centralized dashboard for navigation to all features.  

### Attendance Page  
- Input attendance data by mess number or student identifier.  
- Automatically updates the CSV file with the format:  
  - Column A: Mess No./Student ID  
  - Column B: Name  
  - Column C: Attendance Count  
- Ensures efficient tracking and management of attendance records.  

### View Attendance  
- Displays attendance details of all students in a table format for quick access and review.  

### Edit Attendance Records  
- Provides functionality to correct attendance entries, including adding or subtracting attendance units.  

---

## Technology Stack  
- **Programming Language**: Java  
- **GUI Framework**: Java Swing  
- **Data Handling**: CSV files  

---

## Installation and Setup  

### Prerequisites  
- **Java Development Kit (JDK)** version 8 or higher.  

### Clone the Repository  
```bash  
git clone https://github.com/a-rehman-s/Attendance-Management.git  
cd  Attendance-Management
```  

### Compile and Run  
```bash  
javac -cp . *.java  
java -cp . Main  
```  

### CSV Files Connected  
Ensure the CSV files are saved in the specified directory ('D') as defined in the program.  

---

## Usage  
1. Launch the application and log in using admin credentials.  
2. Navigate to the Home Page for accessing various features.  
3. Use the Attendance Page to input or update attendance data.  
4. View and edit attendance records as necessary.  

---

## Design  
- **Theme**: Light and professional color scheme.  
- **UI Elements**: User-friendly and intuitive layout for smooth operation.  

---

## Contribution  
Contributions are welcome! Follow these steps to contribute:  
1. Fork the repository.  
2. Create a new branch:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Commit your changes:  
   ```bash  
   git commit -m "Added feature-name"  
   ```  
4. Push the branch:  
   ```bash  
   git push origin feature-name  
   ```  
5. Create a Pull Request.  

---

## Contact  
For questions or suggestions, feel free to reach out:  

**Name**: Abdur Rehman Saeed  
**Email**: abdurrehmansaeed709@gmail.com  
**LinkedIn**: https://www.linkedin.com/in/abdur-rehman-saeed-1099271a6/
