Here's a concise and clear `README.md` for your Python + Docker project:

---

````markdown
# Python Docker App

A simple Python app that prints a string, containerized using Docker.
([Project URL](https://roadmap.sh/projects/basic-dockerfile))

## 🐳 Prerequisites
- Docker installed ([Install Guide](https://docs.docker.com/get-docker/))
- `requirements.txt` file (can be empty if no packages needed)

## 🚀 How to Run

1. **Clone the repository**
```bash
git clone <your-repo-url>
cd <repo-name>
````

2. **Build the Docker image**

```bash
docker build -t python-docker-app .
```

3. **Run the container**

```bash
docker run --rm python-docker-app
```

## 📁 Project Structure

```
├── Dockerfile
├── requirements.txt
└── test.py
```

## 🔒 Notes

* Runs as a non-root user inside the container for security.
* Logs are unbuffered for real-time output.

```

---

Let me know if you'd like to add sections like “How to deploy”, “Contributing”, or “License”.
```