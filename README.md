# Algo Stars - Python Repository

### Welcome to the Python repository of Algo Stars! 🐍
We will update new problem statements on starting of the each week. Follow the readme to know how to contribute to this repository.

## How to Collaborate

Contributing to Algo Stars is straightforward. Follow the steps below:

### Forking the Repository

1. Navigate to the repository you want to contribute to (e.g., `Algo-Stars/Python`).
2. Click on the "Fork" button in the top right corner of the page.
   - This creates a copy of the repository in your GitHub account.

### Cloning the Forked Repository

1. On your forked repository, click on the "Code" button, and copy the URL.
2. Open your terminal and run the following command, replacing `<your-username>` with your GitHub username:

   ```bash
   git clone https://github.com/<your-username>/Python.git
   ```

### Making Changes

1. Navigate to the problem statement directory (e.g., `basic/week1/`).
2. Solve the problem using the online program editor linked in the README.
3. Save your solution in a file named `<your-username>_week<week-number>_challenge.<programming-language-extension>`.

### Pushing Changes

1. In the terminal, navigate to your cloned repository:

   ```bash
   cd Python
   ```

2. Add your changes and commit:

   ```bash
   git add .
   git commit -m "Solved basic week 1 problem"
   ```

3. Push the changes to your GitHub repository:

   ```bash
   git push origin main
   ```

### Creating a Pull Request

1. Visit your forked repository on GitHub.
2. Click on the "Pull Requests" tab.
3. Click the "New Pull Request" button.
4. Set the base repository to `Algo-Stars/Python` and the base branch to `main`.
5. Set the head repository to `<your-username>/Python` and the compare branch to `main`.
6. Click the "Create Pull Request" button.
7. Add a title and description, then click "Create Pull Request" again.

Congratulations! You've just contributed to Algo Stars!!!

## Features and Events

### Weekly Winners 🏆

- Each week, we pick winners from each difficulty level based on the runtime of their solutions.
- Winners are featured on the leaderboard and eligible for monthly prizes.

### Monthly Prizes 🎁

- At the end of the month, the top 3 contributors from the leaderboard receive amazing prizes from Algo Stars.

## Leaderboard System

### Weightage Balancing System


1. **Assign Weights:**
   - Assign a weight to each difficulty level.
   - These weights reflect the relative difficulty or complexity of each level.

2. **Calculate Weighted Scores:**
   - Multiply the raw score of each participant by the corresponding weight of the difficulty level.
   - This gives you a weighted score for each participant based on the difficulty level they attempted.

3. **Normalize Runtimes:**
   - Normalize the runtime values. You can use a formula to scale the runtimes, so they are on a comparable scale across different difficulty levels. For example, you might divide the runtime by the maximum allowed runtime for each difficulty level.

4. **Calculate Runtime Scores:**
   - Subtract the normalized runtime from a base value (e.g., subtract from 100). The idea is to reward lower runtimes with higher scores.

5. **Combine Scores:**
   - Add the weighted score and the runtime score for each participant to get their total combined score.

6. **Rank Participants:**
   - Rank participants based on their total combined scores. The participant with the highest total combined score will be ranked first, and so on.

### Here's a simplified example:

- Participant A:
  - Basic: 80 points, Runtime: 10 seconds
  - Intermediate: 120 points, Runtime: 15 seconds
  - Advanced: 150 points, Runtime: 20 seconds
  - Weighted Score: (80 * 1) + (120 * 1.5) + (150 * 2) = 560
  - Normalized Runtimes: 10/15/20 seconds
  - Runtime Scores: 100 - 10, 100 - 15, 100 - 20
  - Combined Score: Weighted Score + Sum of Runtime Scores

- Participant B:
  - Basic: 100 points, Runtime: 8 seconds
  - Intermediate: 90 points, Runtime: 12 seconds
  - Advanced: 180 points, Runtime: 18 seconds
  - Calculate Weighted Score as before
  - Normalized Runtimes: 8/12/18 seconds
  - Runtime Scores: 100 - 8, 100 - 12, 100 - 18
  - Combined Score: Weighted Score + Sum of Runtime Scores

## File Naming Conventions

When submitting solutions, follow the suggested naming convention:

```
<your-username>_week<week-number>_challenge.<programming-language-extension>
```

For example: `colddsam_week1_challenge.py`

### Leaderboard Display

The leaderboard is updated weekly, showcasing contributors with the highest total scores. Monthly prizes are awarded to the top 3 contributors.

## Connect with Us

Follow us on social media for updates and announcements:

- [Twitter](https://twitter.com/AlgoStars)
- [LinkedIn](https://www.linkedin.com/company/algo-stars)
- [Instagram](https://www.instagram.com/algostars_official)

Happy Coding! 🚀🌟
