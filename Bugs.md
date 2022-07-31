# Bugs

- User details not taken automatically with authentication, have to put in through settings + UX of this screen is not so good (Hostel name is in black and the rest of the content is in grey).
![Screenshot_2022-07-31-14-24-05-284_club devsoc csaapp](https://user-images.githubusercontent.com/101785829/182018815-0672d519-2a53-4daa-bcb9-4dd257ae1050.png)

- Welcomes you with something went wrong, please check your net
  ![Screenshot_2022-07-31-14-24-35-940_club devsoc csaapp](https://user-images.githubusercontent.com/101785829/182018817-4a3639f9-8625-4774-9dc3-3994a13d9681.png)
  
- Splash screen + login screen shown  ```onResume``` instead of onCreate

- Text goes out of screen on eating options tab
![Screenshot_2022-07-31-14-23-37-208_club devsoc csaapp](https://user-images.githubusercontent.com/101785829/182018807-d5e155ce-54d5-41f9-a741-36ee66309137.png)

- Grievance page doesn't work + can't exit the perpetual loading sign by tapping outside it( make ```closeOnTapOutSide(true)```)

![Screenshot_2022-07-31-14-24-42-141_club devsoc csaapp](https://user-images.githubusercontent.com/101785829/182018818-a07d94f2-517d-42e2-af5e-ab632d1625e7.png)

- Location of back button on top left is not same across screens. For example, the location of back button is different in Settings and User details screen

- If we click on the contact button in CSA Bearers then it is not just redirecting you to contacts app with the phone number written; instead it is initiating call by itself which is sometimes anoying + it requires call permission from the user.
