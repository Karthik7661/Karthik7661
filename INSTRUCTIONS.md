# 🚀 How to Publish Your New Attractive GitHub Profile

To make this beautiful profile live on your GitHub account, follow these simple steps:

### Step 1: Create the Special Profile Repository on GitHub
1. Open your browser and go to: **[Create New Repository](https://github.com/new)**.
2. Under **Repository name**, type: `Karthik7661` *(this must match your username exactly)*.
3. You will see a message: *"You found a secret! Karthik7661/Karthik7661 is a special repository..."*
4. Select **Public** *(must be public to display on your profile)*.
5. **CRITICAL**: Do **NOT** initialize with a README, `.gitignore`, or license. Leave them all unchecked.
6. Click **Create repository**.

---

### Step 2: Push the Files from Your Computer
Open a terminal in the folder where these files are located (`/Users/skarthik/Downloads/gittask`), and run the following commands:

```bash
# 1. Initialize a new git repository
git init

# 2. Add all files (README, assets, workflows)
git add .

# 3. Create your initial commit
git commit -m "Initialize professional animated profile"

# 4. Rename the default branch to main
git branch -M main

# 5. Link it to your GitHub repository
git remote add origin https://github.com/Karthik7661/Karthik7661.git

# 6. Push to GitHub
git push -u origin main
```

---

### Step 3: Enable Permissions for the Snake Game Action
The Snake Game Contribution Grid runs on GitHub Actions to auto-update every 24 hours. You need to give the Action permission to commit the SVG to your repo:
1. Go to your repository on GitHub: **`https://github.com/Karthik7661/Karthik7661`**.
2. Click on **Settings** (top bar).
3. In the left sidebar, expand **Actions** and click on **General**.
4. Scroll down to the **Workflow permissions** section.
5. Select **Read and write permissions**.
6. Click **Save**.

---

### Step 4: Run the Action Manually (to generate the snake immediately!)
1. Click on the **Actions** tab in your repository.
2. Click on **Generate Snake** on the left menu.
3. Click the **Run workflow** dropdown on the right, and then click **Run workflow**.
4. Wait 1 minute. Once it completes, your snake graph is generated and will show up on your profile!

🎉 Enjoy your beautiful new profile!
