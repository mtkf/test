## Hello Fan
My first github, enjoy!

How to build a github Repository

### 1. enter root
'''
sudo -i
'''

### 2. add a new github repository in github websit
for example https://blog.csdn.net/Hanani_Jia/article/details/77950594

### 3.make your local git directories
my github workspace is /home/fan/git/

### 4.clone repository to local
entry /home/fan/git
'''
git clone https://github.com/mtkf/test.git
'''
then you can github and test folder
the test folder is the project you build on the webset 

### 5. push a file to remote github
make a file in the test folder
...
vi hello.md
...
save the file

'''
git add hello.md
git commit -m hello
git push origin master
'''

then you can find the hello.md in the website of github test project

### 6. modify and push to remote
modify hell0.md

一般步骤：
git add hello.md

git commit -m hello
git pull origin master(你自己的分支)
git push -u origin master
如果过程中出现‘please enter a commit message…’,首先esc然后输入 ：wq即可

https://blog.csdn.net/guo_lei_lamant/article/details/79175443
