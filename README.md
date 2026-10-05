# Terraform Docker Project

## 📌 About

This is a beginner-level **Infrastructure as Code (IaC)** project using **Terraform and Docker**.

In this project, Terraform is used to create an **Nginx Docker container** automatically.

## 🛠️ Technologies

* Terraform
* Docker
* Nginx

## 📂 Project Structure

```text
terraform-docker/
├── main.tf
└── README.md
```

## 🚀 Steps to Run

### 1. Initialize Terraform

```bash
terraform init
```

### 2. Check the plan

```bash
terraform plan
```

### 3. Create the container

```bash
terraform apply
```

Enter:

```text
yes
```

### 4. Check the container

```bash
docker ps
```

Open in browser:

```text
http://localhost:8080
```

### 5. Check Terraform State

```bash
terraform state list
```

### 6. Destroy the container

```bash
terraform destroy
```

Enter:

```text
yes
```

## 🎯 What I Learned

* Basics of Terraform
* Infrastructure as Code (IaC)
* Terraform with Docker
* `terraform init`
* `terraform plan`
* `terraform apply`
* `terraform state`
* `terraform destroy`

## 👨‍💻 Author

**Dharani Kumar**

B.Tech Information Technology Graduate
