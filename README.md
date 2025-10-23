Assignment 1: GitHub Basics

- Created a repository named MyFirstRepo.
- Added a README.md with my introduction.
- Learned how to commit and push files.
# Clone your repo
git clone https://github.com/your-username/MyFirstRepo.git
cd MyFirstRepo

# Create assignment.txt
echo "Assignment 1: GitHub Basics" > assignment.txt
echo "- Created a repository named MyFirstRepo." >> assignment.txt
echo "- Added a README.md with my introduction." >> assignment.txt
echo "- Learned how to commit and push files." >> assignment.txt

# Commit and push
git add assignment.txt
git commit -m "Add assignment.txt with initial content"
git push
