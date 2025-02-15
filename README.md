**⚡ Generative AI Blog Generation Application (AWS) ⚡**
**📌 Project Overview**

🔹 Engineered an end-to-end Generative AI application on AWS to auto-generate blog content.
🔹 Utilized AWS services and AI models to enable dynamic content generation based on user queries.

**🛠️ Technologies Used**

1. Boto3 – Integrated AWS services programmatically.
2. Amazon S3 – Stored generated blog content with timestamping.
3. API Gateway – Exposed REST API for user interaction.
4. AWS Lambda – Handled backend processing via serverless functions.
5. Postman – Tested API endpoints efficiently.

**🚀 Key Features**

1. Seamless AI Integration: Connected AWS Lambda to Amazon Bedrock’s Meta Llama 2 13B model via Boto3.
2. Dynamic Content Generation: Processed user queries and generated blog content in real-time.
3. Optimized Performance: Configured AWS IAM roles, policies, and Lambda timeouts for efficient execution.
4. Automated Storage: Stored AI-generated blog text files in S3 with timestamping.
   
**📂 Project Structure**
*📖 How It Works*

1️⃣ User Query: Sent via API Gateway (REST API).
2️⃣ Processing: AWS Lambda invokes Amazon Bedrock’s Meta Llama 2 13B model using Boto3.
3️⃣ Content Generation: AI generates a blog post based on the query.
4️⃣ Storage: Generated blog is stored in S3 with a timestamped filename.
5️⃣ Response: The blog content or S3 file link is returned to the user.
