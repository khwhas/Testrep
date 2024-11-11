Section 1: How to add a directory to the repository and then to push. 

*****************************Section 1*****************************
mkdir Codes
cd Codes
mkdir Python_Codes
mkdir C++_Codes
cd ..
ls
touch Codes/Python_Codes/.gitkeep
touch Codes/C++_Codes/.gitkeep
git add .
git commit -m "Added Codes folders with Python_Codes and C++_Codes subfolders"
git pull --rebase origin main
git push origin main
*******************************************************************
