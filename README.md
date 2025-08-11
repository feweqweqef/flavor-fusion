# flavor-fusion
My first cloud computing project - A responsive recipe website built and hosted on AWS.

*Flavour Fusion* is a dynamic recipe recommendation website designed to make discovering, exploring, and sharing recipes more enjoyable and personalized. I built it with a fully serverless architecture using AWS services. The project combines intuitive UI, cloud scalability, and smart user interactions to deliver a seamless cooking experience.

## Key Features
- Exploring Recipes
- Smart Filtering & Search
- 'Add your own recipes' section
- Food Culture Section
- User Authentication
- AI Chatbot Assistant

## 🧰 Tech Stack & AWS Services Used

| Feature | Technology |
|--------|------------|
| Frontend Hosting | Amazon S3 |
| Backend Logic | AWS Lambda |
| Database | Amazon DynamoDB |
| REST APIs | Amazon API Gateway |
| Authentication | Amazon Cognito |
| Chatbot | Amazon Lex |
| Frontend UI | HTML, CSS, Bootstrap, JavaScript |
| Integration Tool | Kommunicate (for Lex bot integration) |


## Security

- Used IAM roles to securely allow Lambda functions to access DynamoDB
- Cognito provides secure login flows and password policies
- CORS enabled on API Gateway for safe frontend/backend integration

  ## Further Documentation

- 📄 [Project Report (CTEC REPORT.docx)](./docs/CTEC%20REPORT.docx)
- 📊 [Presentation Slides (CTEC SLIDES.pptx)](./docs/CTEC%20SLIDES.pptx)
- 🔗 [Live Site (hosted on S3)](https://flavour-fusion-bucket.s3.amazonaws.com/index.html) - Not available as off now as I have shut down the active services. Please refer to the youtube video demo for an extensive overview
- 📹 [Demo Video](./docs/youtube_link.txt)

This project was created by **Hafeezah Binte Abdul Kasim**.The project reflects my passion for web development, cloud computing, and building user-centric applications with real-world impact.
