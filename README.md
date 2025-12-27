# n8n Automation Platform

![n8n Banner](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

**Secure Workflow Automation for Technical Teams**

n8n is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n lets you build powerful automations while maintaining full control over your data and deployments.

![n8n Interface Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Core Capabilities

*   **Hybrid Development:** Seamlessly switch between visual node-based building and writing custom JavaScript/Python code. Install npm packages directly within workflows.
*   **AI-Native Architecture:** Build sophisticated AI agent workflows using LangChain. Integrate LLMs with your private data sources and custom models securely.
*   **Deployment Flexibility:** Self-host on your own infrastructure (Docker, Kubernetes, npm) for maximum data privacy or utilize the managed cloud offering.
*   **Enterprise Ready:** Features include granular user permissions, SSO integration, and support for air-gapped environments.
*   **Vibrant Ecosystem:** Access over 400 integrations and 900+ production-ready workflow templates.

## Quick Start

Get up and running in seconds using `npx` (requires [Node.js](https://nodejs.org/)):

bash
npx n8n


Alternatively, deploy using Docker for a containerized environment:

bash
# Create a persistent volume
docker volume create n8n_data

# Run the container
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n


Access the editor at `http://localhost:5678`.

## Documentation & Resources

*   **[Official Documentation](https://docs.n8n.io):** Comprehensive guides and API references.
*   **[Integration Directory](https://n8n.io/integrations):** Explore all available connectors.
*   **[Workflow Templates](https://n8n.io/workflows):** Import ready-to-use automation blueprints.
*   **[LangChain Guide](https://docs.n8n.io/langchain/):** Deep dive into AI capabilities.
*   **[Community Forum](https://community.n8n.io):** Get support and share knowledge.

## Licensing

n8n is distributed under the **[Sustainable Use License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md)** and the **[n8n Enterprise License](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md)**.

This "fair-code" model ensures:
*   **Source Availability:** The source code is always visible.
*   **Self-Hosting Freedom:** Deploy the software anywhere.
*   **Extensibility:** You can create and integrate your own nodes.

Commercial support and enterprise features are available via the Enterprise license. For details, refer to the [License Documentation](https://docs.n8n.io/reference/license/).

## Contributing

We welcome contributions! Please see our [Contributing Guide](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) for details on how to report bugs, suggest features, and submit pull requests.

## Careers

Interested in working on the future of automation? Visit our [Careers Page](https://n8n.io/careers).

## Pronunciation

**n8n** stands for "nodemation" and is pronounced "n-eight-n".