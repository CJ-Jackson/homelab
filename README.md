# CJ's Homelab

The manifest of the of my Kubernetes Homelab I got running at Home, hence Homelab.

This project utilizes [Infrastructure as Code (IaC)](https://en.wikipedia.org/wiki/Infrastructure_as_code) and [GitOps](https://www.weave.works/technologies/gitops) principles to significantly leveraging [FluxCD](https://fluxcd.io/) to streamline the management of my homelab’s self-hosted services. By defining infrastructure configurations as code and leveraging Git for version control and automated deployment, I can fully automate the provisioning of new services, continuously operate them with minimal manual intervention, and efficiently update existing configurations without downtime. This approach ensures consistency, repeatability, and reduces the risk of human error in managing my local development environment.

## What is a Homelab?

> At its core, a Homelab is a personal server setup – typically using your own home network – that you build and maintain to experiment with, learn about, and run services in a controlled environment. Think of it as your own miniature IT infrastructure, mimicking what you might see in a larger company or data centre.

## Benefit of having a Homelab?

- **Safe Space to Fail:** This is arguably the biggest benefit. A homelab provides a risk-free environment to experiment with new technologies, tools, and configurations without impacting production systems or your personal data. You can break things, learn from mistakes, and rebuild – all without consequences.
- **Hands-on Learning:** Theory is great, but practical experience is invaluable. A homelab lets you do things – install software, configure networks, deploy applications, troubleshoot problems – reinforcing what you’ve learned.
- **Explore New Technologies:** Want to try a new database, container orchestration system (like Kubernetes), or serverless framework? Your homelab is the perfect place to dip your toes in without a huge investment.
- **Skill Development:** Building and maintaining a homelab forces you to develop valuable skills in areas like system administration, networking, security, and DevOps.
