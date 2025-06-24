# 🚀 Git ke Intermediate Commands

Ye file un logon ke liye hai jo basic Git commands seekh chuke hain aur ab intermediate level pe aage badhna chahte hain.

---

### 1. `git diff`
- Working directory aur staging area ke beech ka difference dikhata hai.
- Changes dekhne ke liye useful hai before committing.

---

### 2. `git reset filename`
- Staging area se kisi file ko hata deta hai.
- Use karo agar galti se `git add` kar diya ho.

---

### 3. `git reset --hard`
- Pure project ko last commit ki state me le jata hai.
- ⚠️ Changes permanently delete ho jate hain.

---

### 4. `git stash`
- Temporary tarike se current changes ko side me rakh deta hai.
- Useful jab kaam chodke branch switch karna ho.

---

### 5. `git stash apply`
- Stash me rakhe gaye changes ko wapas laata hai.

---

### 6. `git remote -v`
- Connected remote URLs dikhaata hai (origin ka path verify karne ke liye).

---

### 7. `git push -u origin branch-name`
- Nayi branch ko remote pe push karne ke liye.
- `-u` se default tracking set ho jata hai.

---

### 8. `git fetch origin`
- Remote repo se latest changes ko download karta hai bina merge kiye.

---

### 9. `git rebase branch-name`
- Branch ko update karta hai clean history ke sath (merge commit ke bina).
- Caution: Use carefully in team projects.

---

### 10. `git cherry-pick commit-id`
- Kisi specific commit ko current branch me copy karta hai.

---

### 11. `git revert commit-id`
- Kisi galat commit ko undo karta hai, but safe way me (new commit create hota hai).

---

### 12. `git log --oneline --graph --all`
- Short aur graphical view deta hai git history ka.
- Branch aur merge ka structure dekhne ke liye best hai.

---

### 📌 Tip:
Ye commands sikhne ke baad tu Git ke kaafi powerful tools ko handle karne lagta hai. Practice karte raho aur real projects me use karo.

---

