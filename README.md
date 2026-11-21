# Awesome Agent Sandboxes

A curated directory of secure sandboxes, micro-VMs and code interpreters for running AI-generated code.

## 📑 Table of Contents

- [Browser Sandboxes (1)](#browser-sandboxes)
- [Code Interpreters (3)](#code-interpreters)
- [Dev Environments for Agents (9)](#dev-environments-for-agents)
- [Managed Sandbox APIs (5)](#managed-sandbox-apis)
- [MicroVM Runtimes (3)](#microvm-runtimes)
- [Open-Source Sandboxes (3)](#open-source-sandboxes)


## Browser Sandboxes

- [StackBlitz](https://stackblitz.com/) - Browser-based development environment powered by WebContainers, enabling full Node.js stacks to run entirely in the browser. Provides instant sandboxes for web development and testing. ([Read more](/details/stackblitz.md)) `Freemium` `Browser` `WebContainers` `Web Development`

## Code Interpreters

- [Binder](https://mybinder.org/) - Free service for building and sharing interactive computing environments from Git repositories, powered by Jupyter and BinderHub. Enables ephemeral code execution environments without local setup. ([Read more](/details/binder.md)) `Free Plan` `Open Source` `Code Interpreter` `Jupyter` `Free`
- [Jupyter](https://jupyter.org/) - Open-source web application for interactive computing, supporting live code, visualizations, and narrative text across many programming languages. Widely used as a code interpreter for data science and AI workflows. ([Read more](/details/jupyter.md)) `Open Source` `Free Plan` `Code Interpreter` `Data Science`
- [Replit](https://replit.com/) - Browser-based integrated development environment and code execution platform with built-in AI agent features. Supports collaborative coding and instant deployment of applications. ([Read more](/details/replit.md)) `Freemium` `API` `AI-Powered` `Browser` `IDE`

## Dev Environments for Agents

- [Coder](https://coder.com/) - Platform for provisioning remote development environments on any infrastructure, with self-hosted and managed options. Supports Terraform-based workspace provisioning and team access controls. ([Read more](/details/coder.md)) `Open Source` `Self-Hosted` `Enterprise` `API` `Remote Development` `Freemium`
- [CodeSandbox SDK](https://codesandbox.io/) - Cloud development platform with an SDK for embedding browser-based sandboxes and dev environments into applications. Supports collaborative coding and instant environment provisioning. ([Read more](/details/codesandbox-sdk.md)) `Freemium` `API` `Browser` `Web Development`
- [Daytona](https://daytona.io/) - Open-source dev environment engine for provisioning ephemeral, secure environments for AI agents and developers. Supports self-hosted and cloud deployment with SDKs for environment lifecycle management. ([Read more](/details/daytona.md)) `Open Source` `Self-Hosted` `API` `Dev Environments` `Freemium`
- [Devpod](https://devpod.sh/) - Open-source tool for creating reproducible development environments in any cloud or local infrastructure using dev containers. Provides CLI and UI for managing remote development backends. ([Read more](/details/devpod.md)) `Open Source` `Self-Hosted` `Free Plan` `Dev Containers`
- [Eclipse Che](https://www.eclipse.org/che) - Developer workspace server and cloud IDE that provides multi-user, container-based workspaces for teams. Supports Kubernetes-native workspaces and custom machine images. ([Read more](/details/eclipse-che.md)) `Open Source` `Self-Hosted` `Enterprise` `Kubernetes`
- [GitHub Codespaces](https://github.com/features/codespaces) - Cloud-hosted development environments integrated with GitHub, providing disposable virtual machines and containers for code execution. Supports preconfigured environments and VS Code in the browser. ([Read more](/details/github-codespaces.md)) `Freemium` `API` `Cloud` `IDE`
- [Gitpod](https://gitpod.io/) - Automated developer environments that spin up cloud IDEs from repositories, supporting prebuilds and team collaboration. Offers self-hosted and managed deployment options. ([Read more](/details/gitpod.md)) `Freemium` `Self-Hosted` `API` `Cloud IDE`
- [Northflank](https://northflank.com/) - Developer platform offering ephemeral environments, preview deployments, and managed infrastructure for running code. Supports automated environment creation for AI agent workflows. ([Read more](/details/northflank.md)) `Freemium` `API` `Cloud` `Ephemeral Environments`
- [Runloop](https://runloop.com/) - Cloud development environments designed for AI agents, offering secure, disposable sandboxes for running and testing code. Provides APIs for environment provisioning and code execution. ([Read more](/details/runloop.md)) `Paid` `API` `AI-Powered` `Cloud`

## Managed Sandbox APIs

- [Cloudflare Sandbox SDK](https://cloudflare.com/) - Cloudflare provides sandboxed execution for Workers and edge functions using V8 isolates, with SDKs for deploying untrusted code at the edge. Includes isolation and resource limits for safe code execution. ([Read more](/details/cloudflare-sandbox-sdk.md)) `Freemium` `API` `Edge` `V8 Isolates`
- [E2B](https://e2b.dev/) - Secure cloud sandboxes for running AI-generated code, primarily Python, with SDKs for integrating code execution into AI agents. Offers persistent file systems and long-running sessions. ([Read more](/details/e2b.md)) `Freemium` `API` `AI-Powered` `Python`
- [Modal Sandboxes](https://modal.com/) - Managed cloud platform for running sandboxed code, functions, and AI workloads with automatic scaling and volume storage. Provides isolated execution environments accessible via API. ([Read more](/details/modal-sandboxes.md)) `Paid` `API` `AI-Powered` `Enterprise` `Cloud`
- [Riza](https://riza.io/) - Code execution API for AI agents, providing isolated sandboxes for running untrusted code in multiple languages. Includes session management and artifact handling for agent workflows. ([Read more](/details/riza.md)) `Paid` `API` `AI-Powered` `Code Execution`
- [Vercel Sandbox](https://vercel.com/) - Vercel provides preview and deployment sandbox environments for frontend and full-stack applications, enabling isolated execution of serverless functions. Used for testing AI-generated code in preview deployments. ([Read more](/details/vercel-sandbox.md)) `Freemium` `API` `Cloud` `Serverless`

## MicroVM Runtimes

- [CloudHypervisor](https://cloudhypervisor.org/) - Open-source virtual machine monitor optimized for cloud workloads, supporting KVM and modern hardware virtualization features. Designed for lightweight, secure microVMs in cloud-native environments. ([Read more](/details/cloudhypervisor.md)) `Open Source` `Self-Hosted` `MicroVM` `KVM`
- [Firecracker](https://firecracker-microvm.github.io/) - Open-source microvirtual machine monitor for creating secure, multi-tenant container and function services. Used by AWS Lambda and Fargate for lightweight virtualization. ([Read more](/details/firecracker.md)) `Open Source` `Self-Hosted` `MicroVM` `Virtualization`
- [Kata Containers](https://katacontainers.io/) - Open-source lightweight virtual machines that provide stronger isolation for container workloads using hardware virtualization. Compatible with Kubernetes and container runtimes for secure multi-tenant execution. ([Read more](/details/kata-containers.md)) `Open Source` `Self-Hosted` `MicroVM` `Kubernetes`

## Open-Source Sandboxes

- [gVisor](https://gvisor.dev/) - User-space kernel for containers that provides an additional layer of isolation between application code and the host operating system. Used to sandbox untrusted workloads in container environments. ([Read more](/details/gvisor.md)) `Open Source` `Self-Hosted` `Container Sandbox` `Isolation`
- [microsandbox](https://github.com/microsandbox/microsandbox) - Open-source sandbox for safely executing untrusted code in isolated environments. Designed for running AI-generated code with minimal overhead and language-agnostic support. ([Read more](/details/microsandbox.md)) `Open Source` `Self-Hosted` `Free Plan` `Code Execution`
- [Wasmtime](https://wasmtime.dev/) - Standalone WebAssembly runtime for running Wasm modules securely outside the browser, developed by the Bytecode Alliance. Provides sandboxed execution with fine-grained capability-based security. ([Read more](/details/wasmtime.md)) `Open Source` `Self-Hosted` `WebAssembly` `Bytecode Alliance`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg