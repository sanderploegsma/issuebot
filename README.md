# Issuebot
Create GitHub issues by using a slash command in slack.

## Setup
1. Create a new slack command in your Slack team directory
2. Note the token
2. Create a new GitHub access token. Make sure you select the correct scopes. NOTE: issues are created by the GitHub user the token belongs to, you can of course create a seperate account for issues created by this script.
3. Clone this repo somewhere and run `npm install`
4. Host it somewhere, e.g. heroku. Use that hostname in the slack command settings as the command url.
4. Use the environment variables below

## Environment variables
- `SLACK_TOKEN`: the token provided by Slack.
- `GITHUB_REPO`: the repository where the issues should be created
- `GITHUB_TOKEN`: the access token generated by GitHub

## License
This project is licensed under the MIT license.
