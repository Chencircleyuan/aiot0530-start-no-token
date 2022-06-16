# AIot-HW05

## Lecture 14: IoT Flask Web (github, vs code)

### Step 1 : Development Environment Setup in AIot_HW05

1. Please install vs code, register github, install git for windows

2. (check-point 1) github create a new repository (aiot0524)

3. go to vs code clone this repository (choose new branch)

4. vs code 安裝 python extension

5. pip install flask, pandas, sklearn

  快捷鍵 ctrl+shift+p ===> package manager 叫出 (git clone....)

  快捷鍵 ctrl+' ==> 叫出終端機

6. (check-point 2) 為了要upload local file to github from local要終端機 C:> 設定下面 (不設定 branch default ='main')

  C:> git config --global user.name "Chencircleyuan"

  C:> git config --global user.email a0909992729@gmail.com

7. C:> git remote add origin https://github.com/Chencircleyuan/AIot-HW.git

  if you want to change
  git remote add origin https://github.com/Chencircleyuan/AIot-HW.git

  git branch -M main

  git push -u origin main

### Step2 :Install some package
'''
pip insall gunicorn   
Flask==2.0.1 
Jinja2==3.0.1 
psycopg2 
sklearn 
pandas  
numpy 
'''

### Step3
1. open xampp
2. DBMs--> add user/pwd = test123/test123
3. create a database 'aiotdb'
4. create a data table 'sensors.sql'
5. INSERT  `sensors` (`id`, `time`, `value`, `temp`, `humi`, `status`) VALUES INTO sensors
6. save as sensers.sql 

### Step4
1. Open Sublime Text
2. SELECT * FROM sensors
3. set sensors.sql in app.py
4. test running app.py in vs code


### Step5
1. open xampp
2. get http://127.0.0.1:5000 
6. run on website
