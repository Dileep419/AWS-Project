🚀 End-to-End CI/CD Pipeline for React App – Deployment Mastered! 🧑‍💻🌍

👉 Thrilled to share that I’ve successfully set up a complete CI/CD pipeline to automate the deployment of a Reactjs application! This journey was packed with practical learning — from source control to quality assurance, security scanning, and containerised deployment.

🎯 What I Achieved:-
 Designed and implemented an end-to-end deployment workflow where every code change goes through automated testing, scanning, building, and is finally deployed in a Docker Swarm environment — all with zero manual intervention!

🧰 Key Tools & Technologies Involved:
 🔷 Jenkins – Orchestrating the CI process
 🔷SonarQube – Static code analysis for cleaner code
 🔷NPM – App build toolchain
 🔷Docker – Container packaging and delivery
 🔷Trivy – Image vulnerability scanning

🧩 Jenkins Plugins in Play:
 ➜ Node.js Plugin
 ➜Docker Pipeline
 ➜SonarQube Scanner
 ➜Pipeline Stage View
 ➜Eclipse Temurin Installer

🖥️ Infrastructure Architecture (on AWS EC2):
 🔶1x Jenkins Server (t2.large) – CI/CD, Docker, SonarQube
 🔶1x Docker Swarm Master (t2.large) – Orchestration, Trivy
 🔶2x Swarm Workers (t2.micro) – Container hosting

🔄 CI/CD Pipeline Breakdown:
✅ Clean up Jenkins workspace
✅Pull the latest code from GitHub
✅Run code quality analysis (CQA)
✅Enforce quality gate checks
✅Install frontend dependencies
✅Perform a filesystem scan with Trivy
✅Build and push Docker image
✅Run image-level scan via Trivy
✅Deploy containers using Docker Stack

🚢 Deployment Strategy:
 Zero-downtime delivery through Docker Swarm, enabling continuous availability even during deployment.

✅ Outcome:
 A production-grade, automated CI/CD flow with integrated quality and security gates. Every commit is now just a push away from production!
🔚 From code to production – faster, safer, and smarter!
