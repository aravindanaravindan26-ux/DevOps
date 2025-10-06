---

# ☁️ 6. AWS Cloud Basics

## 🔹 What is Cloud Computing?
Using remote servers to store and run applications instead of local machines.

---

## 🔹 AWS Core Services
| Service | Description |
|----------|--------------|
| EC2 | Virtual servers |
| S3 | Object storage |
| IAM | Access control |
| VPC | Virtual network |
| CloudWatch | Monitoring |

---

## 🔹 Launch EC2 Instance
1. Login to AWS Console  
2. Go to EC2 → Launch Instance  
3. Select Ubuntu → t2.micro (Free tier)  
4. Create a key pair  
5. Connect via SSH:
   ```bash
   ssh -i "key.pem" ubuntu@<public-ip>
