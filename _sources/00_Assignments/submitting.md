### How to Commit and Push a File to GitHub Using VS Code Source Control Panel
1. **Save your work**
From the menu at the top of the notebook, select Restart kernel then Run all to check that your code runs without error. Then Save the notebook.

Make sure the notebook is in the github repository folder corresponding to that assignment (e.g. ps03.ipynb should be in the folder assignments-gitusername/PS01)

1b. Before submitting, check that the top directory of your current VS Code session is your assingments-<githubusername> directory.

**Submitting Code - (Option 1)**
2. Uncomment the code in the final cell of the notebook and run that cell. This will commit and submit your work.

**Submitting Code - (Option 2)**
2. **Stage the File**  


    Open the Source Control panel in VS Code by clicking on the Source Control icon in the Activity Bar (or pressing `Ctrl+Shift+G` / `Cmd+Shift+G` on macOS). Locate the file you want to stage under "Changes" and click the `+` icon next to it.

2. **Commit the Changes**  
    In the text box at the top of the Source Control panel, type a meaningful commit message. Then click the checkmark icon (`✔`) to commit the staged changes.

3. **Push to GitHub**  
    Click on the three-dot menu (`...`) in the Source Control panel and select `Push`. Alternatively, you can use the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P` on macOS), type "Git: Push," and press Enter.

4. **Verify the Changes**  
    Go to your GitHub repository in a web browser to confirm the file has been updated.

### Example
1. Stage `submitting.md` by clicking the `+` icon next to it.
2. Commit with the message: "Add instructions for committing and pushing files."
3. Push the changes to the `main` branch.
