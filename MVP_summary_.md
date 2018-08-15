## Intrepreting Creative Writing

### Project Fletcher MVP Summary

### Harmeet Hora

### Domain:

I will be using the Reddit API to get data from the /r/writingprompts subreddit. This is a subreddit that is dedicated to creative writing. The premise is that a user posts a prompt for other users to write a piece about. An example of a top rated writing prompt is "[Your roommate is obviously an alien trying to infiltrate humanity... but he pays the rent on time so you don't really care.](https://www.reddit.com/r/WritingPrompts/comments/97375a/wp_your_roommate_is_obviously_an_alien_trying_to/)" 

I plan to analyze prompt posting users and prompt responding users, as well as the corrsesponding scores associated with them. I am familiar with the domain as a casual reader of the subreddit and a very frequent user of Reddit overall.

### Data:

| Field           | Description                      | Data type |
| --------------- | -------------------------------- | --------- |
| Prompt          | The actual writing prompt        | String    |
| Prompt_author   | User that posted prompt          | String    |
| Num of Comments | Number of responses to a prompt  | String    |
| Prompt Rating   | Net Rating (upvotes-downvotes)   | Integer   |
| Response        | Response text                    | String    |
| Response Rating | Net Rating (upvotes-downvotes)   | Integer   |
| Response Author | User that posted prompt response | String    |

### Known Unknowns:

- Limitations in pull requests from reddit
- Identify target of clustering
- Separating prompt responses from general comments