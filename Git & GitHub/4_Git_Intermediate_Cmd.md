# 🚀 Git ke Intermediate Commands

Ye file un logon ke liye hai jo basic Git commands seekh chuke hain aur ab intermediate level pe aage badhna chahte hain.

---

### 1. `git diff`
- Working directory aur staging area ke beech ka difference dikhata hai.
- **Use-case:** Commit karne se pehle kya badla hai, dekh lo.

---

### 2. `git reset filename`
- Staging area se kisi file ko hata deta hai.
- **Tip:** Galti se `git add` ho gaya ho to use karo.

---

### 3. `git reset --hard`
- Pure project ko last commit ki state me le jata hai.
- ⚠️ **Warning:** Sab changes delete ho jayenge, soch samajh ke use karo.

---

### 4. `git stash`
- Temporary tarike se current changes ko side me rakh deta hai.
- **Use-case:** Jaldi se branch switch karni ho aur kaam adhura ho.

---

### 5. `git stash apply`
- Stash me rakhe gaye changes ko wapas laata hai.
- **Tip:** `git stash list` se sab stashes dekh sakte ho.

---

### 6. `git remote -v`
- Connected remote URLs dikhaata hai (origin ka path verify karne ke liye).
- **Tip:** Kabhi bhi remote ka URL bhool jao to yeh command use karo.

---

### 7. `git push -u origin branch-name`
- Nayi branch ko remote pe push karne ke liye.
- **Tip:** `-u` lagane se agli baar sirf `git push` likhoge to bhi kaam ho jayega.

---

### 8. `git fetch origin`
- Remote repo se latest changes ko download karta hai bina merge kiye.
- **Use-case:** Sirf dekhna hai ki remote pe kya naya hai, bina apne code ko badle.

---

### 9. `git rebase branch-name`
- Branch ko update karta hai clean history ke sath (merge commit ke bina).
- ⚠️ **Warning:** Team projects me rebase karte waqt dhyan rakho, sabki history badal sakti hai.

---

### 10. `git cherry-pick commit-id`
- Kisi specific commit ko current branch me copy karta hai.
- **Use-case:** Sirf ek hi commit ki changes chahiye ho to.

---

### 11. `git revert commit-id`
- Kisi galat commit ko undo karta hai, but safe way me (new commit create hota hai).
- **Tip:** Team projects me revert safe hai, kyunki history safe rehti hai.

---

### 12. `git log --oneline --graph --all`
- Short aur graphical view deta hai git history ka.
- **Use-case:** Branches aur merges ka structure dekhne ke liye best hai.

---

## ⭐ Best Practices
- Hamesha commit karne se pehle `git status` aur `git diff` check karo.
- Team me kaam karte ho to push/pull se pehle baaki members ko batao.
- Kabhi bhi `git reset --hard` bina soch samjhe mat use karo.
- Regularly `git fetch` aur `git pull` karte raho taaki code updated rahe.

