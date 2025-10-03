# Personal Cyber Threat Intelligence (CTI) Aggregator

![Screenshot of the FreshRSS Dashboard](./assets/dashboard-screenshot.png)

A streamlined, self-hosted system for aggregating, filtering, and categorizing high-value CTI feeds to accelerate threat research and learning.

## The Problem: Information Overload
As a security professional, staying updated with the latest threats, vulnerabilities, and APT activity is crucial. However, the sheer volume of reports from vendors, CERTs, and researchers creates significant noise. Manually sifting through this data is time-consuming and inefficient.

## The Solution: A Curated & Automated CTI Hub
This project uses **FreshRSS**, a powerful open-source RSS aggregator, running in a Docker container to solve this problem. By sourcing high-quality feeds and applying a robust set of filtering rules, it automatically categorizes incoming reports into four key areas:

* **APT & Threat Actors**
* **Malware & Campaigns**
* **Vulnerabilities & Exploits**
* **Strategic & Industry Reports**

This provides a centralized, clean, and searchable dashboard for my daily threat intelligence consumption and ongoing professional development.

## Key Features
* **Automated Aggregation:** Pulls from dozens of national CERTs, security vendors, and top-tier research blogs.
* **Intelligent Filtering:** Utilizes custom rules to automatically categorize articles, saving hours of manual sorting.
* **Self-Hosted & Private:** Full control over my data and workflow, running locally via Docker.
* **Actionable Categories:** Core topics are separated for quick access depending on the research need (e.g., "Find latest malware analysis reports").

## Tech Stack
* **[FreshRSS](https://freshrss.org/)**: The core RSS aggregator engine.
* **[Docker](https://www.docker.com/)**: For easy, containerized deployment.

## Getting Started

### Prerequisites
* Docker and Docker Compose installed.
