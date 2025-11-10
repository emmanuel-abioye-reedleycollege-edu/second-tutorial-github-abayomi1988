# Task 1: Editing, Committing, and Pushing Using GUI

### Objective
Learn how to make your **first commit** using either **Visual Studio Code** or **Microsoft Visual Studio**, working directly with the file `hello-world.cpp`.

---

### Step 1: Open the Repository
- Open **Visual Studio Code** or **Visual Studio IDE**.
- Go to **File → Open Folder...** and select the cloned repository folder.

---

### Step 2: Edit the C++ File
Open `examples/hello-world.cpp` and modify the code by adding three lines using `cout`:

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "My name is [Your Name]" << endl;
    cout << "My lab group number is [Your Group Number]" << endl;
    cout << "My group members are: [List all group members]" << endl;
    return 0;
}
```

---

### Step 3: Save and Commit (GUI Steps)
#### In VS Code:
1. Click the **Source Control** icon on the left sidebar.  
2. You’ll see `hello-world.cpp` listed as a changed file.  
3. Click the **+** icon to stage the change.  
4. Type a commit message, e.g., “Added name and group info.”  
5. Click the **✓ Commit** icon.  
6. Click **Sync Changes** or **Push** to upload to GitHub.

#### In Visual Studio IDE:
1. Open the **Git Changes** window (View → Git Changes).  
2. Stage the modified file by checking it.  
3. Write a commit message and click **Commit All**.  
4. Click **Push** to send your commit to GitHub.

---

🎯 You’ve now made your first GUI-based Git commit!
