# git commands to sync submodules
git submodule update --remote --recursive
git add .
git commit -m "sync with rubikscube submodules"
git push