project_root/
│── backend/
│   │── model_api/
│   │   │── app.py  # FastAPI app for AI inference
│   │   │── model.py  # Load and process AI model
│   │   │── requirements.txt  # Dependencies
│   │   │── Dockerfile  # Containerization
│   │── data_service/
│   │   │── app.py  # Handles data storage and retrieval
│   │   │── database.py  # PostgreSQL/MongoDB integration
│   │   │── Dockerfile
│── frontend/
│   │── app/  # React or Vue.js frontend (optional)
│── infrastructure/
│   │── k8s/
│   │   │── model_api_deployment.yaml
│   │   │── data_service_deployment.yaml
│   │   │── postgres_deployment.yaml
│   │   │── load_balancer.yaml
│   │── docker-compose.yaml  # Local dev setup
│── benchmarks/
│   │── load_test.py  # Locust-based load testing
│── docs/
│   │── evaluation_report.md  # Comparison & recommendation
│── README.md  # Project documentation
