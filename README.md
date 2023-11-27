# state-transitions-challenge

## 1. Write down the different states e.g. sign-up page
* Sign-up page
* Log-in page
* Logged-in page

## 2. Write down the different events e.g. user logs in
* User inputs invalid sign-up details
* User signs up
* User clicks log-in link
* User clicks sign-up link
* User inputs incorrect log-in details
* User logs in
* User logs out

## 3. Determine which events cause a transition between one state and another
* User signing up
* User clicks log in link
* User logging in
* User clicks sign up link
* User logging out

## 4. Make this into a state transition diagram
<img width="569" alt="Screenshot 2023-11-27 at 16 58 29" src="https://github.com/karysbarbrook/state-transitions-challenge/assets/101115101/414c965a-1948-4bab-ae98-c4c822975c7a">

## 5. Draw up a state transition table, based on your diagram, populating the table below

| Initial State | Event                    | Next State               |
| ------------- | ------------------------ | ------------------------ |
| Sign-up page  | Invalid sign-up details  | Sign-up page             |
| Sign-up page  | Sign up                  | Log-in page              |
| Sign-up page  | Click log-in link        | Log-in page              |
| Log-in page   | Incorrect log-in details | Log-in page              |
| Log-in page   | Click sign up link       | Sign-up page             |
| Log-in page   | Log in                   | Logged-in page/home page |
| Logged-in page| Log out                  | Log-in page              |

## 6. Design a test case that covers all states and all events/transitions at least once i.e. what is the starting state and what events (in what order) are required

### Covering all states test:

| Events                   | States                   |
| ------------------------ | ------------------------ |
| Start  | Sign-up page             |
| Click log-in link                  | Log-in page              |
| Log-in       | Logged-in page              |


