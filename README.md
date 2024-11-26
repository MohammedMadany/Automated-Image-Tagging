# **Automated Image Tagging System**
## **Introduction**
The Automated Image Tagging System is a powerful tool designed to simplify and enhance the process of assigning descriptive tags to images. Built using Microsoft’s Florence2 model and deployed on AWS Cloud Services, the system enables businesses to manage, search, and utilize vast image datasets efficiently. This project demonstrates how AI and machine learning can revolutionize visual content management across industries.

## **Key Features**
- Image Classification and Tagging: Leverages Florence2 for high-accuracy image understanding.
- AWS Integration: Utilizes services like S3, SageMaker, API Gateway, and Lambda for seamless deployment.
- Scalability: Supports both enterprise-scale operations and individual use cases via Streamlit Cloud.
- Real-Time Processing: Provides a fast and reliable tagging pipeline with minimal human intervention.
## **Use Cases**
- E-commerce: Enhanced product discoverability through detailed and accurate tagging.
- Healthcare: Supports diagnostic imaging by identifying critical patterns in scans.
- Media Management: Speeds up content organization and retrieval in digital libraries.
- Scientific Research: Assists in geological or mineral classification tasks.
## **Technologies Used**
- Machine Learning: Florence2 for advanced visual understanding.
- Cloud Infrastructure: AWS services (S3, Lambda, SageMaker, CloudWatch) for robust deployment.
- Web Interface: Streamlit for intuitive, user-friendly interactions.
## **How It Works**
1. Image Upload: Users upload images through a REST API or Streamlit interface.
2. Processing: Images are analyzed using Florence2, hosted on AWS SageMaker.
3. Tag Generation: Descriptive tags are generated and stored in the system for retrieval.
4. Logging and Monitoring: Amazon CloudWatch ensures transparency and performance tracking.
