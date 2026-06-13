# Blog Abstract: Superlog on OpenShift

- **Thesis:** Deploying an open-source observability platform like Superlog on OpenShift demonstrates that complex TypeScript monorepos with database dependencies can be containerized with UBI images and deployed with minimal friction.
- **Target Audience:** Platform engineers, SREs, and DevOps teams evaluating self-hosted observability for OpenShift AI workloads.
- **Blog Type:** Red Hat Developer Blog
- **Key Points:**
  1. UBI containerization of pnpm monorepos requires specific permission handling for Node.js workspaces
  2. OpenShift's built-in binary build strategy handles multi-layer Node.js builds efficiently
  3. OpenTelemetry-native observability tools complement AI workload monitoring on OpenShift AI
- **Products:** Red Hat OpenShift AI, Open Data Hub, Red Hat UBI
- **CTA:** Try deploying your own observability stack on OpenShift with AutoPoC.
- **Proposed Outline:**
  1. What is Superlog?
  2. Why observability matters for AI workloads
  3. Containerizing a TypeScript monorepo with UBI
  4. Building and deploying to OpenShift
  5. Validating the deployment
  6. Lessons learned
  7. Try it yourself
