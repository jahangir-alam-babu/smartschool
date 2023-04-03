
# SmartSchool

Our school management system is an all-in-one solution designed to streamline the administrative and management tasks of academic institutions. It comes with a range of features such as classes, students, teachers, exams/grades, notice, event, syllabus, routine, academic, promotion, payment, staff, and library management.

The classes feature allows schools to create, manage and schedule classes for their students with ease. The system also enables schools to create student profiles, manage student attendance, and maintain academic records. Teachers can easily track student progress, record attendance and grades, and communicate with parents and students via the notice and event management module.

The syllabus and routine management features enable schools to create and manage academic syllabus, assign tasks, and schedule regular classes. The academic management feature assists with tracking student performance, promotions, and achievements. The payment management feature ensures easy payment of school fees and other dues. The staff management module enables schools to manage their staff by creating employee profiles, maintaining their records, and tracking their performance. Finally, the library management feature allows schools to manage their library books, track book issuance, and returns.

Our school management system offers a user-friendly interface, simplifying the process of managing academic institutions, saving time and resources while improving productivity and efficiency.





## Badges

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Features

- Classes
- Students
- Teachers
- Exams / Grades
- Notice
- Event
- Syllabus
- Routine
- Academic
- Promotion
- Payment
- Staff
- Library


## Run Locally

Clone the project:

```bash
  git clone 
```

Go to the project directory:

```bash
  cd smartschool
```

Install the project dependencies using Composer:

```bash
  composer install
```

Create a copy of the .env.example file and rename it to .env:

```bash
  cp .env.example .env
```

Generate an application key:

```bash
  php artisan key:generate
```

Set up your database by editing the .env file and entering your database credentials.

Run database migrations:

```bash
  php artisan migrate
```

That's it! You've successfully installed a Laravel project from Git. You can now run the project locally by starting the development server using the command:

```bash
  php artisan serve
```

If you are using laragon then you can ignore artisan serve


## User Login

Email: admin@demo.com
Password: 12345678


## Author

- [@jahangir-alam-babu](https://www.github.com/jahangir-alam-babu)

