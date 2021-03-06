# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Data Science Refresh

Instrutors and Producers: Here is a guide for creating your own "DSI-City-#" student-facing repostitory from the baseline master curriculum. 

> Note: You can [review additional examples of the suggested Github workflow on our Wiki](https://github.com/generalassembly-studio/dsi-course-materials/wiki/Github---Instructor-Workflow). 

## How to Setup a Student Facing Github Repository for Your Course

In many technical courses, we use a student-facing repo to distribute things like homework and project prompts, sample and solution code, slides and notes. The instructor or producer should create a student-facing repo for each course by following these steps:

* Before you get started, you'll need to know the GitHub usernames for your instructors' and TAs'. They should already have GitHub accounts but if they don't, they'll need to sign up for one. Instructor/TA onboarding is a great time to ask for their GitHub handles. 

* Instructors and TAs should first create a "staging" branch off of the "DSI-Course-Materials" repository for any immediate edits to baseline course materials. Give this branch a descriptive name like: "DSI-NYC-1-staging". This is a good place to work when adapting lessons and labs, and makes it easy to submit Pull Requests back to the master or log issues.

* Next, create a fork of the "DSI-Course-Materials" repository. This fork should live under the [ga-students org](https://github.com/ga-students) (if you don't have access to ga-students, please email [Zoe](mailto:zoes@generalassemb.ly) to be given access). Name your repo using the following convention: [Course Code]-City-Instance Number (i.e. "DSI-NYC-1"). **Make sure that you set your fork to "Private" in order to prevent the course materials from being publicly accessible**.

* You'll now need to [create a new team](https://github.com/orgs/ga-students/teams) and add all of your course instructors and TAs to this team. Give your team the same name that you gave the repo above, plus the word "Instructors" (i.e. "DSI-NYC-1 Instructors"). Then, under "Repositories," add the repo that you just created by searching for its name in the "Add repositories" field. Finally, press the "Settings" button on the left and select "Admin Access". This will allow your instructors to make changes to the repo.

* You should also add your instructional team (Instructors & TA's) to the ***"DSI-Global-Instructor"*** group. This group should be given read access to all local market repositories, so that instructors can better share resources and see how other markets are implementing materials.

* Your instructors should receive an email notification from GitHub letting them know that they've been given access to this repo but just in case they don't, you can always send them the link. Navigate to [https://github.com/ga-students](https://github.com/ga-students) in your web browser, search for your repo by name in the "Find a repository..." search box and click on the title for your repo. This is the permalink for your repository that you can send to instructors and students. 

* When adding students to the repo, do the same as above, creating a team for students (i.e. "DSI-NYC-1 Students"). Instead of giving students admin access to the repo, give them read access. This way, students can't accidentally write over any files in the repo. __Producers will need to add students to this group because instructors do not have the necessary permissions to add students.__ You will need to ask students to send you their GitHub account names either before the start of class or during the first week so that you can add them. 

* Your student-facing repo should now be ready to use! Once your instructors have access, they should be able to add any content that they need to distribute to students to the repo (homework, project prompts, resources, etc.). Depending on the course, students will either use the GitHub for Mac/Windows client or the command line  to pull down files from the class repo.

##Questions?

If you have any questions, please visit [the GA help desk](http://ga.co/helpdesk).

