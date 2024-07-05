
🌐 Deploying and Optimizing Guestbook App with Redis Memory Data Structure and Redundancy in OpenShift Internal Registry on Kubernetes 
🐳 1- Initial Deployment: Built and deployed a simple Guestbook application, an essential first step to get accustomed to deploying in a cloud environment.
 
- Deployment and Application Update:
• Optimized Dockerfile for Guestbook app.
• Pushed Guestbook image to IBM Cloud Container Registry.
- Autoscaling and Performance Management (HPA):
• Implemented Horizontal Pod Autoscaler.
• Verified correct scaling based on demand.
- Rollout and Rollback:
• Observed v2 Guestbook app post-deployment.
• Successfully rolled back update when needed.
 
🛠️ 2- Advanced Deployment with OpenShift: The most critical part of my project was deploying the Guestbook application from the OpenShift internal registry. This phase included:
 
• Utilizing OpenShift image streams for seamless updates.
• Deploying a multi-tier version of the application, enhancing the initial architecture with better data management and optimized performance.
• Updating the application to ensure message persistence, significantly improving user experience.
