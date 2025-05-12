
This example template assumes you do not have a college degree. If you do have a college degree be sure to include a section for your education details.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>John Doe Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            max-width: 800px;
        }
        h1, h2, h3 {
            margin: 10px 0;
        }
        p, ul {
            margin: 5px 0;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <h1>John Doe</h1>
    <p>Seattle, WA</p>
    <p>Phone: (123) 456-7890</p>
    <p>Email: john.doe@email.com</p>
    <p>LinkedIn: <a href="https://linkedin.com/in/johndoe">linkedin.com/in/johndoe</a></p>
    <p>GitHub: <a href="https://github.com/johndoe">github.com/johndoe</a></p>

    <h2>Professional Summary</h2>
    <p>Cloud Engineer with 3 years of experience in deploying and managing cloud infrastructure on AWS and Azure. Skilled in DevOps practices including CI/CD pipelines, containerization with Docker and Kubernetes, and Infrastructure as Code using Terraform. AWS Certified Solutions Architect with a track record of improving deployment efficiency by 30%. Dedicated to optimizing cloud performance and reliability.</p>

    <h2>Skills</h2>
    <ul>
        <li>Cloud Platforms: AWS, Amazon Web Services, EC2, S3, RDS, Lambda, Azure, Google Cloud</li>
        <li>DevOps Tools: Docker, Kubernetes, Jenkins, Git, Ansible, Terraform, Helm</li>
        <li>Programming: Python, Bash, PowerShell</li>
        <li>Monitoring: Prometheus, Grafana, CloudWatch</li>
        <li>Networking: VPC, DNS, Load Balancers, Firewalls</li>
        <li>Methodologies: Agile, Scrum, Problem-Solving</li>
    </ul>

    <h2>Certifications</h2>
    <ul>
        <li>AWS Certified Solutions Architect - Associate, 2023</li>
        <li>HashiCorp Certified: Terraform Associate, 2024</li>
        <li>Certified Kubernetes Administrator (CKA), 2024</li>
    </ul>

    <h2>Work Experience</h2>
    <h3>Cloud Engineer</h3>
    <p>Tech Solutions Inc., Seattle, WA</p>
    <p>June 2022 - Present</p>
    <ul>
        <li>Deployed AWS infrastructure using Terraform, reducing provisioning time by 40%.</li>
        <li>Built CI/CD pipelines with Jenkins and Git for 20 weekly deployments.</li>
        <li>Managed Kubernetes clusters to achieve 99.99% application uptime.</li>
        <li>Automated monitoring with Prometheus and Grafana, cutting incident response time by 25%.</li>
    </ul>

    <h3>Junior DevOps Engineer</h3>
    <p>Innovate Systems, Portland, OR</p>
    <p>March 2020 - May 2022</p>
    <ul>
        <li>Configured Docker containers to support 50% increase in application traffic.</li>
        <li>Wrote Python and Bash scripts to automate tasks, saving 10 hours weekly.</li>
        <li>Collaborated with teams to integrate security into CI/CD pipelines.</li>
    </ul>

    <h2>Projects</h2>
    <h3>Serverless Web Application</h3>
    <p>GitHub: <a href="https://github.com/johndoe/serverless-app">github.com/johndoe/serverless-app</a>, January 2023 - March 2023</p>
    <ul>
        <li>Built serverless application with AWS Lambda, API Gateway, and DynamoDB.</li>
        <li>Used Terraform for Infrastructure as Code to enable scalable deployments.</li>
    </ul>

    <h3>Kubernetes Homelab</h3>
    <p>GitHub: <a href="https://github.com/johndoe/k8s-homelab">github.com/johndoe/k8s-homelab</a>, September 2023 - Present</p>
    <ul>
        <li>Created multi-node Kubernetes cluster with Helm charts and ingress controllers.</li>
        <li>Implemented Prometheus and Grafana for real-time monitoring.</li>
    </ul>

    <h2>Education</h2>
    <p>Cloud Computing Bootcamp</p>
    <p>Coursera, Completed May 2022</p>
    <ul>
        <li>6-month program covering AWS, Docker, Kubernetes, and CI/CD.</li>
    </ul>
    <p>Self-Directed Learning</p>
    <ul>
        <li>Online courses in Python (Coursera) and Kubernetes (Udemy), 2023-2024.</li>
    </ul>
</body>
</html>
```

Things that help with ATS.

- Clean structure. Use semantic HTML that ATS can parse when copied into text fields.
- No complex styling. Minimal CSS, basic fonts and margins ensures content remains intact when stripped to plain text.
- Avoid special characters that can be parse incorrectly like "•" characters, images or non-standard fonts.
- Test with ATS resume checkers. Jobscan, Resunate to verify keyword matches and readability.