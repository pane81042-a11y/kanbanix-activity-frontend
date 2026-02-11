# Kanbanix Activity Frontend

Kanbanix Activity Frontend is responsible for displaying activity logs and system events across boards and tasks.

It provides visibility into user actions and workflow history within the Kanbanix platform.

## Features

- View task activity history
- View board level activity
- User action logs
- Timestamped system events
- Filter activity by user or date
- API integration with Activity Service

## Architecture

Built with:

- React
- Webpack Module Federation
- Axios for API communication
- Shared UI component library
- Dynamic integration with Kanbanix Shell

This microfrontend is independently deployable and loaded at runtime by the Shell.

## AWS Always Free Tier Deployment

Deployed using a serverless architecture:

- Amazon S3 for static hosting
- Amazon CloudFront for CDN distribution
- GitHub Actions for CI/CD automation
- AWS IAM for secure deployment access

Deployment Flow:
1. Code pushed to GitHub
2. CI pipeline builds the project
3. Static assets uploaded to S3
4. CloudFront cache invalidated

## Scalability

- Independent deployment cycle
- CDN optimized delivery
- No server management required
- Easily extendable logging views

## Portfolio Value

Demonstrates:

- Event driven UI design
- Microfrontend isolation
- Cloud based static hosting
- Enterprise level activity tracking interface
