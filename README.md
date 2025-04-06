# 🚀 MCP-AWS: AI Agent for AWS EC2 Management

Welcome to **MCP-AWS**, a simple yet powerful AI-driven application that leverages OpenAI Agents and MCP servers to manage AWS EC2 instances. This app allows you to provision and terminate EC2 instances using natural language commands in your terminal. 🖥️✨

---

## 🌟 Features

1. **Provision EC2 Instances**: Just tell the AI agent to create an EC2 instance, and it will handle the rest, providing you with the instance ID. 🛠️
2. **Terminate EC2 Instances**: Provide the instance ID, and the agent will terminate the instance for you. ❌
3. **MCP Server Integration**: Explore how custom MCP servers can be created and integrated with OpenAI Agents SDK. 🧩

---

## 🛠️ Tools in the MCP Server

The MCP server is a custom server with two tools:
1. **`initiate_aws_ec2_instance`**: Creates an AWS EC2 instance.
2. **`terminate_aws_ec2_instance`**: Terminates an AWS EC2 instance by its ID.

---

## 🚀 Getting Started

### Prerequisites
1. **Python 3.12+**: Ensure you have Python installed.
2. **AWS IAM Role**: Create an IAM role with the necessary permissions to manage EC2 instances.
3. **Environment Variables**: Prepare a `.env` file with the following variables:
   - `AWS_ACCESS_KEY_ID`
   - `AWS_SECRET_ACCESS_KEY`
   - `AWS_DEFAULT_REGION`
   - `OPENAI_API_KEY`

### Installation
1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd mcp-aws