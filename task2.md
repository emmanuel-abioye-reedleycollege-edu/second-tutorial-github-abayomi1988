# Task 2: Branching and Merging (GUI)

### Objective
Learn to create a branch, make changes, and merge it back to main using the GUI in your IDE.

---

### Step 1: Create a Branch
#### In VS Code:
- Open the **Source Control** panel → Click **Branches** → **Create new branch**.  
- Name it something like `update-greeting`.

#### In Visual Studio IDE:
- Go to **Git → New Branch** → Enter branch name `update-greeting` → **Create**.

---

### Step 2: Modify Code
In `hello-world.cpp`, add another line of output, for example:
```cpp
cout << "This message is from my update-greeting branch!" << endl;
```

---

### Step 3: Commit and Merge
1. Stage and commit the change.  
2. Switch back to the **main** branch.  
3. Merge your branch:
   - In VS Code: Click **Branches → Merge Branch → update-greeting → main**.  
   - In Visual Studio: **Git → Merge Branches → Select branch → Merge**.

---

### Step 4: Push to GitHub
Push your updated main branch so changes appear online.
