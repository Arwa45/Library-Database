# Library-Database
# Buisness Rules:
<font size="6">
  An <b>academic library</b> is a well-organized place at college that helps students improve their skills and gives them and the lecturers a proper environment to study and conduct their research. </br>

1)Each lecturer that teaches at the college has an ID, a name, an email address, a phone number, and teaches one or more courses</br>

2)Each student has an ID, a name, an email address, a phone number, and a degree such as freshman, sophomore, junior, senior, postgraduate…etc</br>

3)Each Librarian has an ID, phone number, a name, a shift, and salary.</br>

4)Each Book has an ISBN, a name, content, and a section. Components of section are section name, and section shelf.</br>

5)A book can be borrowed by one or more lecturers, while a lecturer can borrow one or more books.</br>

6)A book can be read by one or more users, a user can read one or more books. </br>

7)A librarian can issue one or more books, while a book can be issued by only one librarian.</br>

8)A writer has an ORCID, a name, an email, a phone number, and a type such as author, scientist, researcher…etc.</br>

9)A book can be written by one or more writers, and a writer can write one or more books.</br>

10)A PC has an IP-address and a password.</br>

11)A PC can be accessed by one or more lecturers, while a lecturer may access as many pcs as he likes per day.</br>

12)A student can access only one PC, and a PC may be accessed by only one student.</br>

13)Librarian can assign as many PCs as he can per day, and a PC can be assigned by only one Librarian.</br>

14)A publishing house has a publisher-id, a name, a phone number, and an email-address.</br>

15)A book can be published by one or more publishing houses, a publishing house can publish one or more books.</br>
</font>

# ERD

![image](https://github.com/Arwa45/Library-Database/assets/102920573/0d6584f6-b3c7-4bec-afbe-26520ca7d0f9)

# EER

![image](https://github.com/Arwa45/Library-Database/assets/102920573/39c20586-d296-4418-a851-323d30017202)

While we were viewing our ERD, we noticed that there are common attributes between 2 entities, the students and the lecturers…
So…
We used the Generalization method.
We created a new entity called users as a Super class, where a user must be either a lecturer or a student but not both.

# Relational model:

![image](https://github.com/Arwa45/Library-Database/assets/102920573/e2b48863-76d2-4232-b005-06707e98d699)
