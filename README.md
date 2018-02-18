##### ใช้คำสั่ง ansible-playbook เพื่อติดตั้งแพคเกจ
```bash
ansible-playbook -i "localhost," -c local install.yml
```

##### เมื่อต้องการอัพเดท ansible roles 
```bash
ansible-galaxy install -r requirements.yml -p ./roles/ --ignore-errors --force
```
---
