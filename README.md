# SAP Landing Zone on AWS (CloudFormation)

This repository contains a minimal CloudFormation template to deploy a **basic Landing Zone for SAP workloads** in AWS.

🛠️ **Resources provisioned**:
- VPC (`10.0.0.0/16`)
- Public and Private Subnets
- Internet Gateway (IGW)
- Public Route Table with default route (`0.0.0.0/0 → IGW`)
- Security Group (SSH and ICMP access)

🎯 **Use case**:  
Kickstart infrastructure for SAP HANA or SAP S/4HANA deployment in a secure and repeatable way.

---

## 🔁 How to use

1. Go to the [AWS CloudFormation console](https://console.aws.amazon.com/cloudformation/).
2. Choose **"Create Stack" → "With new resources (standard)"**.
3. Upload `sap_landing_zone.yaml` from this repo.
4. Follow the wizard to deploy the stack.

> 💡 This setup stays within the **AWS Free Tier** — perfect for labs, demos, or learning.

---

## 📎 Files

| File | Description |
|------|-------------|
| `sap_landing_zone.yaml` | CloudFormation template |
| `diagram.png` *(optional)* | Visual architecture overview (you can add this) |

---

## 👤 Author

**Juan Guillermo Vélez Pérez**  
SAP Cloud Architect | Infrastructure as Code enthusiast  
🔗 [linkedin.com/in/juanguillermovélezpérez](https://www.linkedin.com/in/juanguillermov%C3%A9lezp%C3%A9rez/)

---

## 📄 License

This project is open-source under the MIT License.

