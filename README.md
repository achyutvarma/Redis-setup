---

Redis installation and setting up credentials
✅ Step 1: Update System Packages
sudo apt update
sudo apt upgrade -y

---

✅ Step 2: Install Redis
sudo apt install redis-server -y

---

✅ Step 3: Enable Redis to Start on 
sudo systemctl enable redis

---

✅ Step 4: Start Redis Service
sudo systemctl start redis

---

✅ Step 5: Check Redis Status
sudo systemctl status redis
You should see output indicating it's active (running).
configuring credentials to redis
![image](https://github.com/user-attachments/assets/8822ca91-a9e6-4529-a1ca-5104339126a2)




Follow above process to set up password for redis.


