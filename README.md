# 1. App

https://transactions-3-api-f5211832b8a3.herokuapp.com/

# 2. Running my App (Postman): 

![alt text](<Screenshot 2026-05-22 195146.png>) ![alt text](<Screenshot 2026-05-22 195229.png>) ![alt text](<Screenshot 2026-05-22 195242.png>)

# 3. Running my App (Browser): 
![alt text](<Screenshot 2026-05-22 191047.png>) ![alt text](<Screenshot 2026-05-22 203959.png>)

# 4. Differences: What differences did you note from deploy-app-02-s26 and deploy-app-03-s26?
Authentication, middleware, user model and Mongoose was added in deploy-app-03-s26.

# 5. Models: What model code do you prefer, 02's or 03's?
I prefer 03's model code.

# 6. Challenges: Write the challenges you faced during this exercise and how you solved them
One challenge I faced during this exercise was connecting the API to MongoDB Atlas. The application initially failed to connect because I typed the wrong password in the MongoDB connection URL.

Another challenge occurred when I tried to seed the Atlas database from Heroku by running command:
`
heroku run npm run seed
`
but it did not work and I corrected the command to:
`
heroku run "npm run seed:users"
`

# 7. Questions: Write any questions you still have after this exercise about the code that was here
N/A
