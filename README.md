# hf-model-serving
End-to-end LLM inference service: FastAPI + HuggingFace, containerized for Kubernetes with autoscaling, telemetry, and latency monitoring

This project implements an LLM inference service built with FastAPI and HuggingFace Transformers, containerised with Docker and deployable on Kubernetes. It includes schema-validated APIs with Pydantic, observability with Prometheus + Grafana, and CI/CD automation for reproducible builds. The system is benchmarked under load, with low-latency, and scalable model serving.
