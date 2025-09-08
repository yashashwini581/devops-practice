1️⃣ Initialize a Repo

mkdir devops-practice
cd devops-practice
git init


👉 You created a new folder devops-practice and turned it into a Git repo.
Think of this as giving your folder a brain 🧠 (Git starts tracking versions inside it).

2️⃣ Add a File

echo "Linux Notes - Day 1" > linux-notes.txt


👉 Created your first file with some notes inside.
It’s like writing your first page in a new notebook 📒.

3️⃣ Stage the File

git add linux-notes.txt


👉 Told Git: “Hey, please remember this file in the next snapshot.”
This is like putting the page in the scanner tray 🖨️ before actually scanning it.

4️⃣ Commit the File

git commit -m "Added Linux basics notes"


👉 Git actually saved a version snapshot of your file with your message.
This is the “click photo” 📸 step.

5️⃣ Create Repo on GitHub
👉 You created a repo with the same name online (devops-practice).
This is like reserving your locker in the cloud ☁️.

6️⃣ Link Local to GitHub

git remote add origin https://github.com/yourusername/devops-practice.git


👉 Connected your local folder’s brain 🧠 with the online GitHub repo.
Like saying: “This notebook belongs to that cloud locker.”
