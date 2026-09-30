# Instructions: Kanban Fundamentals with GitHub

Follow the steps below to complete the **Kanban Fundamentals** assignment.  
Screenshots and your reflection will be submitted in Canvas.

---

## 1. Make a new GitHub Repository
1. Select **File → New Repository**.  
2. Name the repository "Kanban Practice" 
3. Add all of the zip file contents to this new pository.  

---

## 2. Make an Initial Local Change
1. Open the repo folder on your computer.  
2. Edit `intro.txt` using a text editor (e.g., VS Code, Notepad++, or TextEdit).  
   - Add your name and today’s date.  
   - Save the file.  
3. In **GitHub Desktop**:  
   - You should see your file changes listed.  
   - Write a short commit message (e.g., “Added name and date to intro.txt”).  
   - Click **Commit to main**.  
   - Click **Push origin** to sync your changes back to GitHub.  

---

## 3. Create Issues (on GitHub.com)
Some tasks live outside Desktop — you’ll create Issues in the browser.  

1. Go to your repository on **GitHub.com**.  
2. Open the **Issues** tab.  
3. Create at least **5 Issues**.  
   - Each Issue should represent a distinct task (see [`sample-issues.md`](sample-issues.md) for examples).  
   - At least **one Issue must correspond to a code change** you will make in GitHub Desktop (for example: *“Add name to intro.txt”* or *“Update README.md with completion note”*).  

---

## 4. Link a Commit to an Issue (in GitHub Desktop)
This is a critical step: learn how to connect your code changes to Issue.  

### 🔗 Demo: Linking Commits to Issues in GitHub

Follow this example carefully — you’ll repeat the same process with your own Issues.

1. **Create an Issue**

   * In your repo on GitHub.com, go to the **Issues** tab.
   * Click **New Issue**.
   * Title it:

     ```
     Demo: Add my name to intro.txt
     ```
   * Click **Submit new issue**.
   * Notice the Issue number (e.g., `#3`).

---

2. **Edit a File Locally**

   * Open `intro.txt` in your repo folder.
   * Add your name and today’s date under the placeholder.
   * Save the file.

---

3. **Commit in GitHub Desktop**

   * Open GitHub Desktop.
   * You should see your file changes listed.
   * In the **Summary** box, type a commit message that references the Issue:

     ```
     Added my name to intro.txt (Fixes #3)
     ```
   * Click **Commit to main**.
   * Click **Push origin** to sync changes back to GitHub.

---

4. **Check the Issue on GitHub**

   * Go back to the Issue on GitHub.com.
   * Scroll to the bottom — you’ll see your commit message automatically linked.
   * Because you used **Fixes #3**, the Issue will now be **closed automatically** once the commit is on the main branch.
   * If you want to just reference the Issue without closing it, use:

     ```
     Updated intro.txt (Refs #3)
     ```

---

### ✅ What You’ve Learned

* `Fixes #<issue number>` links a commit to an Issue **and closes it automatically**.
* `Refs #<issue number>` links a commit to an Issue **without closing it**.
* This creates **traceability**: anyone can see *what code changes resolved which task*.

### Your Task

1. Pick one of your Issues (e.g., *“Add name to intro.txt”*).  
2. Make the change locally in your repo folder.  
3. In **GitHub Desktop**, write your commit message so it references the Issue number.  
   - Example:  
     ```
     Added my name to intro.txt (Fixes #1)
     ```  
     Replace `#1` with the actual Issue number.  
4. Commit and **Push origin**.  
5. Go back to your Issue on GitHub.com.  
   - You should see your commit linked at the bottom of the Issue page.  
   - If you used “Fixes #1” or “Closes #1,” the Issue will close automatically when you push.  
   - If you only want to reference (not close) the Issue, use wording like:  
     ```
     Updated intro.txt (Refs #1)
     ```  

---

## 5. Create a Kanban Board (GitHub Projects)
1. In your repo on GitHub.com, click the **Projects** tab.  
2. Create a new **Project (Beta)**.  
3. Name it: **Kanban Fundamentals – [Your Last Name]**
4. 4. Choose the **Board** layout.  
5. Create three columns:  
- **To Do**  
- **In Progress**  
- **Done**  

---

## 6. Link Issues to Your Board
1. In your Project board, click **+ Add item → Add from repository issues**.  
2. Add all 5 Issues to the **To Do** column.  

---

## 7. Organize & Assign
1. Add **labels** to at least 3 Issues (e.g., Documentation, Enhancement, Bug).  
2. Assign yourself as the responsible person on at least 2 Issues.  
3. Add at least one **due date**.  

---

## 8. Move Issues Through the Workflow
- Drag at least **2 Issues** to **In Progress**.  
- Drag at least **1 Issue** to **Done**.  

---

## 9. Make a Final Local Commit
Before finishing:  
1. Open `README.md` on your computer.  
- Add one line at the bottom:  
  ```
  Completed Kanban Fundamentals – [Your Name]
  ```  
2. Commit this change in **GitHub Desktop**.  
3. Push your commit to GitHub.  
4. Optionally, link this commit to another Issue (e.g., *“Add completion note to README.md”* → `Closes #5`).  

---

## 10. Submit Your Work
1. Take **screenshots** of your Project board showing Issues in all three columns (*To Do*, *In Progress*, *Done*).  
2. Write a **short reflection (3–5 sentences)**:  
- How does Kanban help visualize and manage analytics work?  
- What benefits do you see from using Issues and a Kanban board?  
3. Submit your screenshots and reflection in Canvas (PDF or DOCX is fine).  

---

## ✅ Checklist Before Submitting
- [ ] Cloned repo in GitHub Desktop.  
- [ ] Edited `intro.txt` locally and committed/pushed.  
- [ ] Created at least 5 Issues on GitHub.  
- [ ] Linked at least 1 commit from GitHub Desktop to an Issue.  
- [ ] Created a Project board with 3 columns.  
- [ ] Linked Issues to the Project board.  
- [ ] Added labels, assignees, and due dates.  
- [ ] Moved Issues across *To Do*, *In Progress*, *Done*.  
- [ ] Made a final commit to `README.md` in GitHub Desktop.  
- [ ] Captured board screenshots and wrote reflection.  

---

## 📖 Helpful Resources
- [Quickstart for Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)  
- [About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)  
- [Using issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues)  
- [Tracking your work with issues (overview)](https://docs.github.com/en/issues/tracking-your-work-with-issues)  

---

