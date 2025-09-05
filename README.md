# FutureCast

FutureCast is a production-ready time series forecasting service powered by Amazon’s Chronos-T5 Small model.

This project demonstrates how to take a pretrained ML model and make it usable in a real-world setting through MLOps best practices:

API Serving → A FastAPI endpoint (/forecast) that takes a sequence of numbers (historical data) and returns future predictions.

Containerization → Packaged into a Docker image for portability.

CI/CD → Automated build and deployment pipeline with GitHub Actions.

Deployment → Runs on [Heroku/Render/Cloud Run] with public API access.

Monitoring → Logs incoming requests and responses for traceability.

🚀 Use Cases

Sales forecasting

Energy demand prediction

Traffic/website visits projection

General numerical trend forecasting

🎯 Why This Project

This project focuses on deployment, automation, and reliability rather than model training. It’s a practical showcase of MLOps skills:

Managing pretrained models in production

Building reproducible pipelines

Deploying to the cloud at scale

