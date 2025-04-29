# Experiment 1: Entity-Relationship (ER) Diagram

## 🎯 Objective:
To understand and apply the concepts of ER modeling by creating an ER diagram for a real-world application.

## 📚 Purpose:
The purpose of this workshop is to gain hands-on experience in designing ER diagrams that visually represent the structure of a database including entities, relationships, attributes, and constraints.

---

## 🧪 Choose One Scenario:

### 🔹 Scenario 1: University Database
Design a database to manage students, instructors, programs, courses, and student enrollments. Include prerequisites for courses.

**User Requirements:**
- Academic programs grouped under departments.
- Students have admission number, name, DOB, contact info.
- Instructors with staff number, contact info, etc.
- Courses have number, name, credits.
- Track course enrollments by students and enrollment date.
- Add support for prerequisites (some courses require others).

---

### 🔹 Scenario 2: Hospital Database
Design a database for patient management, appointments, medical records, and billing.

**User Requirements:**
- Patient details including contact and insurance.
- Doctors and their departments, contact info, specialization.
- Appointments with reason, time, patient-doctor link.
- Medical records with treatments, diagnosis, test results.
- Billing and payment details for each appointment.

---

## 📝 Tasks:
1. Identify entities, relationships, and attributes.
2. Draw the ER diagram using any tool (draw.io, dbdiagram.io, hand-drawn and scanned).
3. Include:
   - Cardinality & participation constraints
   - Prerequisites for University OR Billing for Hospital
4. Explain:
   - Why you chose the entities and relationships.
   - How you modeled prerequisites or billing.

# ER Diagram Submission - Student Name

## Scenario Chosen:
University 

## ER Diagram:

![438631459-469fcbf7-49c2-434c-9374-52161dc36bd5](https://github.com/user-attachments/assets/2523451c-a46b-4b4a-818a-a0ec2c1e56d4)

## Entities and Attributes:
-STUDENT: REG_NO, STUDENT_NAME,EMAIL,PHONE_NO,D.O.B. <br/>
-COURSE: COURSE_NAME, COURSE_ID, PREREQUISITE,NO_OF_CREDITS. <br/>
-INSTRUCTOR:NAME,STAFF_ID,CONTACT,EMAIL,PHONE_NO. <br/>
...

## Relationships and Constraints:
- Relationship1 (Cardinality, Participation)
- Relationship2 (Cardinality, Participation)
...

## Extension (Prerequisite / Billing):
- Explain how you modeled prerequisites or billing.

## Design Choices:
Brief explanation of why you chose certain entities, relationships, and assumptions

## RESULT
