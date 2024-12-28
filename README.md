# Green-GitHub: Auto-Powered Activity Tracker 🌱

Achieve the perfect green streak on your GitHub contributions graph effortlessly with **Green-GitHub**! This repository is powered by GitHub Actions 🚀 to simulate activity on your GitHub profile, ensuring your graph stays green daily. The best part? No setup is required—just fork the repo, star it, and let it work its magic. ✨

## Features 💡

- **Zero Setup**: Fork the repo and star it—you're ready to go. ✅
- **Customizable**: Modify the workflow to match your preferred schedule. 🔧
- **Reliable**: Uses GitHub Actions to ensure daily activity without manual intervention. ⚡

## How It Works 🛠️

1. **GitHub Actions Workflow**: A preconfigured workflow runs every 2nd hour, creating and committing a small change to a dummy file in the repo.
2. **Green Contributions**: Each commit registers as a contribution, keeping your activity graph green. 🟩

## Getting Started 🚀

Follow these steps to get started:

1. **Fork this repository**: Click the **Fork** button at the top-right of this page. 🍴
2. **Star the repository**: Ensure you star the repo to activate the workflow. ⭐

That’s it! The workflow will automatically start running every 2nd hour. ⏰

## Workflow Details 📝

The workflow is defined in `.github/workflows/green-activity.yml` and performs the following steps:

1. Runs every 2nd hour using cron job scheduling.
2. Makes a small modification to `greeting.txt`.
3. Commits and pushes the change back to the repository. 🔄

## Customization 🛠️

- **Change the Cron Schedule**: Modify the `cron` value in the workflow file to change the schedule. For example:
  - `0 0 * * *` runs at midnight UTC.
  - `0 */6 * * *` runs every 6 hours.
- **Modify the Commit Message**: Update the `git commit -m` line to use a custom message.

## Notes 📌

- **Private Repos**: If the repository is private, ensure GitHub Actions are enabled in the repository settings.
- **No Manual Setup**: The workflow is preconfigured, so you don't need to manually generate tokens or adjust permissions.

## License 📜

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Keep your GitHub graph green and vibrant with **Green-GitHub**! 🌟
