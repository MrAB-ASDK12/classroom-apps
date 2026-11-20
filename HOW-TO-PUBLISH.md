# Putting the site on GitHub Pages

You don't need to install anything or use the command line. Everything happens on github.com in a web browser. Chrome works best because it lets you drag whole folders.

## 1. Make a free GitHub account

Go to github.com and sign up. Choose your username carefully, because it becomes part of the web address:

`https://YOUR-USERNAME.github.io/classroom-apps/`

## 2. Create the repository

1. Click **+** in the top-right corner, then **New repository**.
2. Name it `classroom-apps`, or any short lowercase name. The name becomes the last part of the address.
3. Set it to **Public**. A free account can only publish public repositories.
4. Turn on **Add README**, then click **Create repository**.

## 3. Upload the site

1. Unzip `classroom-apps-site.zip` on your computer.
2. In the new repository, click **Add file → Upload files**.
3. Open the unzipped folder, select **everything inside it** (not the folder itself), and drag it onto the upload area. The `index.html` file must end up at the top level of the repository.
4. When the upload finishes, click **Commit changes**. GitHub will replace its starter README with the one from the site.

You may not see the `.nojekyll` file when you select files, because your computer hides files whose names start with a dot. If it doesn't upload, the site usually still works. To add it by hand, click **Add file → Create new file**, name it `.nojekyll`, leave it empty and commit.

## 4. Turn on GitHub Pages

1. In the repository, click **Settings**. Then click **Pages** in the left sidebar.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Choose the branch **main** and the folder **/ (root)**, then click **Save**.
4. Wait a few minutes and refresh. A **Visit site** button appears with your address. The first build can take up to 10 minutes.

## 5. Check it

- Open each app from the homepage.
- On a phone, open the +30 Button in Safari, tap **Share → Add to Home Screen**.

## Updating an app later

Open the app's folder in the repository, for example `job-wheel`. Click **Add file → Upload files**, drag in the new `index.html`, and commit. The live site updates within a few minutes. Teachers' saved data isn't affected, because it lives in their browsers, not on GitHub.

## Things to fill in

- **Math Check-In copy links.** In `math-check-in/index.html`, replace `REPLACE-WITH-GRADE-3-COPY-LINK` and `REPLACE-WITH-GRADES-4-7-COPY-LINK`. Make a clean template Sheet for each version, with the app built in and no student data. Share it as "Anyone with the link can view". Then use its address with `/edit…` changed to `/copy`, like this:
  `https://docs.google.com/spreadsheets/d/SHEET-ID/copy`
  Until you add the links, the buttons say "Copy link coming soon".

## Good to know

- A public repository means anyone can see the apps' code. That's fine here, because no student data is ever stored on GitHub.
- GitHub Pages sites shouldn't collect passwords or payment details, and these apps don't.
