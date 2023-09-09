# K-Conect: A Collaborative Server for University Students

Welcome to the K-Conect project repository! K-Conect is a collaborative server designed to enhance communication and collaboration among university students. This project is deployed using Mattermost on Google Cloud Platform (GCP) and hosted at [unicollab.me](https://unicollab.me/).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

K-Conect is an open-source project aimed at improving the way university students connect and collaborate with each other. It provides a dedicated Mattermost server where students can create channels, send messages, share resources, and engage in discussions related to their academic pursuits and campus life.

## Features

- **Mattermost Integration**: K-Conect is built on Mattermost, a popular open-source messaging platform, ensuring a robust and familiar chat experience for users.

- **Collaborative Channels**: Users can create and join channels specific to their courses, clubs, or interests, making it easy to organize discussions.

- **Resource Sharing**: Share documents, links, and other resources directly within chat channels for seamless collaboration.

- **Google Cloud Platform Deployment**: K-Conect is hosted on Google Cloud Platform, ensuring reliability, scalability, and performance.

- **Custom Domain**: Access the K-Conect server at [unicollab.me](https://unicollab.me/) for a user-friendly and branded experience.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- A Google Cloud Platform (GCP) account.
- A Mattermost server set up on GCP.
- A custom domain or subdomain pointing to your Mattermost server (e.g., unicollab.me).

### Installation

1. Clone the K-Conect repository to your local machine:

   ```bash
   git clone https://github.com/your-username/k-conect.git
   ```

2. Set up the required environment variables:

   ```bash
   export MATTERMOST_URL=https://your-mattermost-server-url.com
   export CUSTOM_DOMAIN=https://unicollab.me
   # Add any other necessary environment variables
   ```

3. Install dependencies and start the K-Conect server:

   ```bash
   npm install
   npm start
   ```

4. Access K-Conect in your web browser at [https://unicollab.me](https://unicollab.me/).

## Usage

1. Sign in to K-Conect using your university email or registration credentials.

2. Explore existing channels or create new ones to join discussions related to your courses or interests.

3. Start conversations, share resources, and collaborate with fellow students.

4. Make the most of K-Conect to enhance your university experience!

## Contributing

We welcome contributions from the community to help improve K-Conect. If you'd like to contribute, please follow our [Contributing Guidelines](CONTRIBUTING.md).

## License

K-Conect is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for your interest in K-Conect! We hope this collaborative server enhances the university experience for students and fosters meaningful connections. If you have any questions or feedback, please don't hesitate to get in touch with us.

[Visit K-Conect](https://unicollab.me/) | [Report an Issue](https://github.com/your-username/k-conect/issues)
