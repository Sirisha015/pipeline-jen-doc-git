
# CI/CD Pipeline with Jenkins, Docker, and GitHub

This is a simple DevOps project that demonstrates how to set up a CI/CD pipeline using Jenkins, Docker, and GitHub.

---

## 📁 Project Structure

- `index.html` - A basic static webpage.
- `Dockerfile` - Used to containerize the web app using NGINX.

---

## ⚙️ Tools Used

- Jenkins (CI/CD)
- Docker (Containerization)
- GitHub (Source Code Management)
- AWS EC2 (Deployment)

---

## 🔁 Pipeline Workflow

1. Jenkins pulls code from GitHub.
2. Builds a Docker image using the Dockerfile.
3. Runs the container on port `8080`.
4. Webpage accessible via `http://<EC2-IP>:8080`.

---

## 🚀 How to Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/Sirisha015/pipeline-jen-doc-git.git

in my own words 
first am created one floder in local and created two files html and docker 
after here github creted one repo name as pipline-jen-doc-git
push code local to github

After am installing jenkins 
