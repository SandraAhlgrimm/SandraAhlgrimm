# Why Java Is Sufficient for Your AI Application

When discussing AI applications, we refer to apps that **leverage** the power of artificial intelligence. These AI models are built upon the impressive work of researchers, particularly experts in Python and Scala machine learning. Fortunately, this groundwork has already been completed and is now available for use.

For Java applications, we have two primary options:

1. **Direct Model Calls via HTTP**:
   - The first option involves directly calling the AI models, typically through HTTP requests.
   - However, it's essential to note that different model providers offer distinct APIs. Unfortunately, due to time constraints or other priorities, they haven't committed to any standardized approach.
   - Additionally, since we're in the early stages of AI development, these APIs are continually evolving. Managing these dependencies can be challenging.

2. **Consuming Model APIs via Frameworks**:
   - The second option is to consume AI models via frameworks such as **SpringAI**, **LangChain4J**, or **Semantic Kernel for Java**.
   - Each of these frameworks defines a standard for developers like me. Whether using the models locally or through a cloud provider, this approach allows flexibility.
   - Importantly, it minimizes the need for extensive code changes when switching models.

In this session, we'll explore the current state, differences, and practical usage of all three options. Let's dive in! 🚀