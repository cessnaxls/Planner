# HouseBoard

A Render/GitHub-ready shared household app for couples/families.

## Features

- Separate logins and profiles
- Create a household or join by invite code
- Family calendar
- Delegated tasks and events
- Complete / Not complete status
- Owner assignment, due dates, priority, recurrence labels
- Manual financial tracking
- Accounts, income/expense transactions, monthly budgets
- Budget progress dashboard
- PostgreSQL sync across individual devices
- Mobile/iPad-friendly UI with zoom locked

## Deploy on Render

1. Unzip this project.
2. Push the contents to a GitHub repository.
3. In Render, choose **New → Blueprint**.
4. Select the repository.
5. Render creates the Node web service and PostgreSQL database from `render.yaml`.
6. Open the Render URL.
7. First person chooses **Create household**.
8. Second person chooses **Join household** with the invite code shown in Settings.
