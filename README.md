# Loud Jira
#### This is a manual testing project of [LOUD](https://www.loudiasi.ro/) site. The Kanban board can be found in [Jira](https://robibejenar.atlassian.net/jira/software/c/projects/LI/boards/3?atlOrigin=eyJpIjoiMDk4ZTFmNjBmNzIxNGMwZGFhMTNmMjMyNTA2ZTU0NjYiLCJwIjoiaiJ9).
#### The project tests the main page of the site and it's features.
## Working of the project
The Kanban board contains the Epic issue `Using the main page`, with 3 stories `Using the header`, `Subscribe to newsletter`, `Footer with contact information`. Every story has at least 3 tests that verify the function of the feature.   

![Screenshot 2024-04-16 at 15 45 26](https://github.com/robi12issv/Loud_Jira/assets/160391019/2d368bc6-4549-4f2e-92cf-dcf4bc7cda42)  

The story `Using the header` verifies if the buttons of the header redirect the user to the correct page. The tests were successful, meaning that each button does the correct action. 
A different test was run for every button.  

![Screenshot 2024-04-16 at 09 39 27](https://github.com/robi12issv/Loud_Jira/assets/160391019/8d6d98a6-a61f-4d9f-a9e5-6846a6e4bd8a)

![Screenshot 2024-04-16 at 15 55 34](https://github.com/robi12issv/Loud_Jira/assets/160391019/3d0560e1-3619-4ae1-8775-f61735e83400)

The story `Subscribe to newsletter` verifies the possible scenaries of submitting an email and subscribing to the newsletter. Two of the tests passed. while one failed and revealed a bug, that was transfered to the development attention.
The feature `Submitting with an incorrect email` failed because the feature did not end with an error, which would have been expected with an invalid email submitted.

![Screenshot 2024-04-16 at 15 58 21](https://github.com/robi12issv/Loud_Jira/assets/160391019/77db497c-bc95-4591-9c5f-267514a03cfc)

![Screenshot 2024-04-16 at 16 16 47](https://github.com/robi12issv/Loud_Jira/assets/160391019/a4b9b903-3b04-4cf5-b1cf-6e52a171bdb6)

## Reports
From a total of 11 tests created:
- 100% were executed;
- 90.9% passed;  
![Screenshot 2024-04-16 at 16 11 27](https://github.com/robi12issv/Loud_Jira/assets/160391019/f0ea98ac-63ae-470f-aab3-985fb17b5a71)
![Screenshot 2024-04-16 at 16 11 33](https://github.com/robi12issv/Loud_Jira/assets/160391019/b595e8f4-3f6c-48bc-9d71-3312fd1255b0)
