model for Guvi Zen Class Database

The database name : guvi_zenDB collections : users, courses, lessons, queries, tasks, codekata, assignments, submissions, feedback,
announcements.

Collections

Users Stores information about the users of the platform. username,email,password ,role (e.g., 'student', 'instructor'),full_name these are the inserted user details

Courses Stores information about the courses available. title(titile of the course),description(short description),level (e.g., 'beginner', 'intermediate', 'advanced'),duration(in months)

Lessons Stores information about the lessons within each course.In detail explaination about the course title,content,order

Queries Stores questions asked by users. username ,course,lesson ,query(enter our queries here),timestamp

Tasks Stores information about tasks assigned to users. title description course username due_date status (e.g., 'pending', 'completed')

Codekata Stores information about coding challenges. title description difficulty(e.g., 'easy', 'medium', 'hard') course username score max_score attempts timestamp

Assignments Stores information about assignments given to students. title description course due_date

Submissions Stores information about student submissions for assignments. assignment usernae submission_link submitted_at grade feedback

Feedback Stores feedback given by instructors for submissions. instructor comments timestamp

Announcements Stores announcements made by instructors. title(eg: class schedule,welcome message ), content(enter announcements here), course ,timestamp
