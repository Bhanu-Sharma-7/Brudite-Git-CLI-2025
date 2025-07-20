# 🛠️ Git ke Basic Commands (Hinglish Explanation)

---

1. `git init` -> Kisi folder ko Git repository me convert karta hai. Isse `.git` folder create hota hai.
   - **Tip:** Naye project me sabse pehle yahi command chalti hai.

---

2. `git status` -> Ye batata hai ki kaunse files me changes hue hain, kaunse staged hain ya nahi.
   - **Scenario:** Jab bhi kuchh badlav karo, pehle `git status` se check karo kya change hua hai.

---

3. `git add .` -> Saare naye aur modified files ko staging area me bhejta hai.
   - **Tip:** Sirf ek file add karni ho to `git add filename` likho.

---

4. `git commit -m "write something here"` -> Staged changes ko commit karta hai with a message.
   - **Tip:** Message hamesha meaningful likho, jaise `git commit -m "login bug fix"`

---

5. `git log` -> Ab tak ke commits ki history dikhata hai.
   - **Tip:** `git log --oneline` se short me history dikhegi.

---

6. `git branch` -> Current branch dikhaata hai, aur naye branches banane ke liye bhi use hota hai.
   - **Example:** `git branch feature1` se nayi branch banegi.

---

7. `git checkout branch-name` -> Kisi branch me switch karne ke liye use hota hai.
   - **Tip:** `git checkout -b newbranch` se nayi branch banti aur switch bhi ho jate ho.

---

8. `git merge branch-name` -> Do branches ke kaam ko combine karne ke liye.
   - **Scenario:** Jab feature branch ka kaam complete ho jaye, to usko main branch me merge karo.

---

9. `git remote add origin https://github.com/username/repo.git` -> Local repo ko remote GitHub repo se connect karta hai.
   - **Tip:** Sirf ek baar har project me lagta hai.

---

10. `git push origin main` -> Local commits ko remote GitHub repo ke `main` branch me bhejta hai.
   - **Tip:** Pehli baar push karte ho to `git push -u origin main` likho.

---

11. `git pull origin main` -> Remote repository ke latest changes ko download karke local repo me merge karta hai.
   - **Scenario:** Team me kaam karte ho to push se pehle hamesha pull karo.

---

12. `git clone https://github.com/username/repo.git` -> Kisi existing remote repo ko apne system me copy karta hai.
   - **Tip:** Pehli baar kisi project par kaam shuru karne ke liye use hota hai.

---

## Common Errors & Solutions

- **error: failed to push some refs**
  - Solution: Pehle `git pull origin main` karo, fir `git push` karo.

- **fatal: not a git repository**
  - Solution: Pehle `git init` karo ya sahi folder me jao.

- **merge conflicts**
  - Solution: Conflicted files ko manually edit karo, fir `git add` aur `git commit` karo.
