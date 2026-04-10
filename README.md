# MT-2026
Weekly Tutorial zip files for Mobile Technology Semester 1 2026

## Setup of LFS
1. Install Homebrew if not already installed

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2. Install Git LFS

brew install git-lfs
git lfs install

3. Track zip files with LFS

git lfs track "*.zip"
git add .gitattributes
git commit -m "Track zip files with LFS"

4. Upload a new file

git add filename.zip
git commit -m "Your message"
git push origin main
