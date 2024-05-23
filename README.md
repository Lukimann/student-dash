# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
# About the app
As a user, for you to be able to integrate wwith the app,yu need to register yourself.You can either register as a schoolowner,a student or an instructor.You should enter your first name,lastname,email,password that you will use and yu also need to confirm your password.If you already ahve an account,you should be able to login using your email and your password.
-When you go to the about ,you should the informaation about virtual learn schools which is the courses we offer and their description.

When you go to the contacts dashboard,you should see the varoious ways you can contact us and give us feedback.

# Signup process
The first a user interacts with our app, they should be able to see a button that when clicked,should take you to a form that enables you to register either as a schoolowner,student or an instructor

# SchoolownerDashboard
Once a schoolowner gets into the owners dashbord,they should be able to see differrent schools they own with the name od the school.They should also be able to delete a school by clicking on the red button at the bottom of every school.As a user who is a schoolowner,you should be able to perform certainn functions.On a schoolowner dashboard,you should be able to see differrent routes that for adding a  school,adding an instructor and adding a student.
   
    -To be able to add a school,a schoolowner should be able click on the createschool route .It will take you to a form that enables  a schoolowner to add a school.
   
   -For a schoolowner to be able to add an instructor, you should  click on link to the addTeacher link.This should take you to a form that enables a person to add tha name,the course_id the instructor will teach and the school_id of the school the technical mentor will teach.

   -For a user to be able to add a student ,they should be click on the addStudent link on the side of the page.This should take them to a form that will enable them to add the name of a student,the course_id of the course the student will learn ,the school_id of the school the student will learn from and the resource where a student will get learning materials from.

   -When a schoolowner wants to logout , they should click onthe sidebar that is written Logout.I t should take you back to the  log in form.

# Student dashboard
When a use is logged in as a student, they should be able to see the assessments,the exams and a logout link on the sidebar.
     -When a user clicks on the exams they should be able to see a quiz where they should see the questions baesd on the specific course.To prevent plagerism, a student cannot be able to copy  paste on a specific  quiz.Once the quiz is submitted,the student should be able to see the score they got on the specific quiz.The link for the quiz is on a sidebar.
    
    -When a user clicks on the logout,they should be to the login page.The logout page should be on a sidebar.

    A user should see the courses they enrolled in with an option for deleting a course.When a student clicks on  the delete button,they should be able to delete a course form their courses.  When a student clicks on a specific course,they should be able to see the link to the resources to the courses they enrolled in.

# Instructor dashboard
When a user registers as an instructor they should be able to see different links as follows:
   The first link is the student Attendance.When an instructor clicks on this link they should be able to add an attendance by adding the id of a student,the id of the school the student is currently in , the id of the course the student takes and the date of the class the student attended

   The second link is the Resource which an instructor can use for a class.The instructorcan decide whether to use a locam file or a link that has the required information by using a form.When the instructor adds the resoursemthey should be able to see the resourse they uploaded.

   The third link is the 