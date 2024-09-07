# Keep Your GitHub Profile Green

This repository contains an automated GitHub Action that runs every day, makes a small change, and pushes it to your repository to keep your profile active.

## Disclaimer: 
This workflow modifies your repository automatically. By forking and using this repository, you take full responsibility for how it's used. I am not responsible for any consequences of running this workflow or any changes it makes to your repository.
#### I personally have it turned off. You can check my commit history from profile.

## 🛠 How to Set It Up

### 1. Fork this Repository

Just click the **Fork** button at the top-right of this repository. This will create a copy of this repository under your own GitHub account.

### 2. Check Your GitHub Action Permissions

For the workflow to work, GitHub Actions needs permission to push changes to your repository. Here's how you can check and configure your permissions:

1. Go to your **repository settings**.
2. Scroll down to **Actions**.
3. Ensure that **Read and write permissions** are enabled under **Workflow permissions**.
   - This allows the action to push changes back to your forked repository.

### 3. Sit Back and Relax 😎

That's it! The workflow will run every day at midnight UTC, append the current date to a file, and push the change. You don’t have to do anything.

The daily updates will ensure that your GitHub contribution graph remains green, even if you're not actively pushing code.

## 🔄 How to Trigger the Action Manually

If you want to trigger the workflow manually (for example, to test it), follow these steps:

1. Go to the **Actions** tab in your forked repository.
2. Select the **Keep Me Alive** workflow.
3. Click on **Run workflow** to manually trigger the workflow.

## ⛔️ How to Turn It Off (And Why You Should)

Keeping your contribution graph green can be fun, but after a while, you may want to turn it off. Here’s why:

1. **Cluttered commit history**: Over time, your repository will accumulate many trivial commits, making the history hard to follow.
2. **False representation of activity**: It might look like you're more active than you actually are, which can be misleading.

### How to Disable the Workflow:

GitHub allows you to **disable workflows** without deleting them. This way, you can pause the workflow temporarily, and re-enable it later if you want.

To disable the workflow:

1. Go to the **Actions** tab of your forked repository.
2. Select the **Keep Me Alive** workflow.
3. Click on the **…** (three dots) menu on the top-right.
4. Select **Disable workflow**.

You can re-enable it at any time by following the same steps and selecting **Enable workflow**.

---

Feel free to fork this repository and start keeping your GitHub profile green effortlessly! 🌟
