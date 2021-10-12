# assign-mentor API

Routes:
/ -> GET -> Home Page
/mentors -> GET -> Get all mentors
/mentors -> POST -> Create a mentor 
/students -> GET -> Get all Students
/students/free -> GET -> Get students with no mentors
/mentors/:id -> GET -> Get student by Mentor ID
/mentors/:id -> POST -> select one mentor and add multiple students
/students/:id -> GET -> Get student by ID
/students/:id/:mentorId -> PATCH -> Get student by ID and change mentor
/students/:id -> DELETE -> Delete student by ID


