# IDM 216 Readme example

![Vercel](https://therealsujitk-vercel-badge.vercel.app/?app=drexel-attendance-k3fveq060-mrpaulphan&style=for-the-badge&logo=false)

**Drexel Attendance** is a web application designed to help Drexel University professors track attendance for their classes easily. The application is built using Next.js and Firebase and is currently under development.

## Table of Contents

- [IDM 216 Readme example](#idm-216-readme-example)
  - [Table of Contents](#table-of-contents)
  - [Prerequisites](#prerequisites)
  - [Getting Started](#getting-started)
  - [Usage](#usage)
  - [Database](#database)
  - [Deploy to Production](#deploy-to-production)
  - [Contributing](#contributing)

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js 18.17.0](https://nodejs.org/en/)
- [pnpm](https://pnpm.io/)

## Getting Started

1. Copy `.env.example` to `.env` and fill in the required values.

To run the development server:

1. Install dependencies: `pnpm install`
2. Start the development server: `pnpm dev`

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application in action.

## Usage

Professors can use Drexel Attendance to generate QR codes for their classes, while students can scan these codes to mark their attendance. The application streamlines the attendance tracking process for both professors and students.

## Database

- [Development Console](https://console.firebase.google.com/u/0/project/drexel-attendance/overview)
- [Production Console](https://console.firebase.google.com/u/0/project/drexel-attendance/overview)

## Deploy to Production

Automatic deployment to production is set up on every push to the `master` branch using Vercel. You can access the live project [here](https://vercel.com/mrpaulphan/drexel-attendance).

## Contributing

We welcome contributions! If you'd like to contribute to this project, please follow our [Contribution Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md).
