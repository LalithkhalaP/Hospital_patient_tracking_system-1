# Hospital_patient_tracking_system-1
Title:Hospital Patient Tracking system.

Submitted by: Nihil dharsini.B.K,Mathumitha sree.M,Lalith khala.P [CSE-B]
Insitution: SRM TRP ENGINEERING COLLEGE.
1.Introduction
 Managing patient records in hospitals is essential for improving healthcare outcomes and supporting SDG 3 (Good Health and Well-Being). This project implements a Hospital Patient Tracking System in C using a Doubly Linked List. The system allows efficient addition, search, update, deletion, and display of patient information.
2. Objectives
To implement a dynamic patient record system using doubly linked lists.

To support essential operations: add, search, update, delete, display.

To demonstrate effective use of data structures in healthcare management.

3. Software Requirements
Language: C

Editor/IDE: VS Code

Compiler: GCC

4. Data Structure Used

Doubly Linked List

Each node contains patient details (ID, Name, Age, Department, Doctor, Status) and pointers to previous and next nodes.
This allows efficient forward and backward traversal and management.

5. Functionalities

1. Add New Patient
2. Display All Patients
3. Search Patient by ID
4. Update Patient Status
5.Delete Patient Record
6. Display Patients by Department
7. Display Critical Patients
8. Forward Traversal
9. Backward Traversal

6. Project Explanation 

This project is a console-based Hospital Patient Tracking System written in C.
It uses a doubly linked list to manage patient records dynamically.
The system allows you to add, search, update, delete, and display patient information efficiently.

Sample patient data is initialized at startup, and users interact with the program through a menu.

This project demonstrates the practical use of linked lists for real-world applications in healthcare record management.
7. Code Explanation 

Patient Structure:
Each patient is represented as a node containing fields like ID, name, age, department, doctor, and status, 
along with pointers to previous and next patients.

Doubly Linked List:
The patient nodes are linked so you can traverse both forwards and backwards.

Core Functions:
initializeSampleData(): Adds 8 sample patients at program start.
addPatient(): Adds a new patient record to the end of the list.
displayAllPatients(): Shows all patient records.
searchPatient(): Finds and displays a patient by ID.
updatePatientStatus(): Updates the status of a patient.
deletePatient(): Removes a patient record by ID.
displayByDepartment(): Lists patients in a specific department.
displayCriticalPatients(): Lists patients marked as "Critical".
displayForward() / displayBackward(): Shows patient IDs from head-to-tail or tail-to-head.

Menu System:
The user is presented with a menu to choose different operations, making the system interactive and user-friendly.
8. Conclusion
The project demonstrates how data structures are used for dynamic management of hospital records. 
The doubly linked list enables efficient insertion, deletion, and bidirectional traversal, 
supporting real-world healthcare management aligned with SDG 3.

9. Future Enhancements
• Persistent storage (file/database)
• User authentication
• GUI interface
• Multi-user/networking support

10. References
• SDG 3 Documentation
• GCC Documentation
• VS Code Documentation
 

