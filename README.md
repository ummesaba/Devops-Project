
# DevOps Project
2	+ author : Umme saba
3	+
This project demonstrates a DevOps workflow using:
4	+
- **Docker** for containerization.
5	+
- **Ansible** for automation.
6	+
- **AWS** for deployment.
7	+
8	+
## Project Structure
9	+
devops-project/
10	+
├── app.py # Flask web application
11	+
├── Dockerfile # Docker configuration
12	+
├── requirements.txt # Python dependencies
13	+
├── deploy.yml # Ansible playbook
14	+
├── inventory # Ansible inventory file
15	+
└── README.md # Project documentation
16	+
17	+
## How to Use
18	+
1. Clone this repository:
19	+
   git clone https://github.com/your-username/devops-project.git
20	+
21	+
2. Build the Docker image:
22	+
   docker build -t devops-flask-app .
23	+
24	+
3. Run the Docker container:
25	+
   docker run -d -p 5000:5000 devops-flask-app
26	+
27	+
4. Deploy to AWS using Ansible:
28	+
   ansible-playbook -i inventory deploy.ym
