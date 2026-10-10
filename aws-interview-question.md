# 🔥 AWS Most Asked Interview Questions

Target: MERN / Node.js developers (approximately 1–4 years' experience)


## 🔥 Most Important for Your MERN Interview

You do **not** need to memorize all 234 questions at once. For a MERN / Node.js developer with approximately 3–4 years of experience, prepare these topics first in priority order. This roadmap complements the full question bank below.

### Priority 1 — Must Know
- EC2
- IAM
- S3
- VPC
- Security Groups
- Application Load Balancer (ALB)
- RDS
- Route 53
- CloudWatch
- Lambda
- SQS
- Docker + ECS
- CI/CD

### Priority 2 — Production / Scenario
- Public Subnet vs Private Subnet
- Internet Gateway vs NAT Gateway
- ALB + EC2 architecture
- Auto Scaling
- S3 + CloudFront
- AWS Secrets Manager
- Blue-Green Deployment
- Docker → ECR → ECS → ALB deployment flow
- GitHub → CI/CD → AWS deployment flow

### Priority 3 — Advanced
- EKS
- Kubernetes on AWS
- DynamoDB
- API Gateway
- AWS KMS
- Event-driven architecture
- AWS serverless architecture

**Recommended preparation order:** Complete Priority 1 first, practise the Priority 2 production scenarios, then move to Priority 3.

---


## 1. AWS Fundamentals
1. What is AWS?
2. Why do we use AWS?
3. What are the major AWS services?
4. What is an AWS Region?
5. What is an Availability Zone (AZ)?
6. What is the difference between a Region and an Availability Zone?
7. What is an Edge Location?
8. What is AWS Global Infrastructure?
9. What is IAM?
10. IAM User vs Role vs Policy?
11. What is an IAM Policy?
12. What is the Principle of Least Privilege?
13. What is the AWS root user?
14. When should you use an IAM Role?
15. AWS Console vs AWS CLI?

## 2. EC2
16. What is Amazon EC2?
17. Why do we use EC2?
18. What is an AMI?
19. AMI vs EC2 Instance?
20. What is an EC2 instance type?
21. What are EC2 instance families?
22. What is a key pair?
23. What is a Security Group?
24. Security Group vs Network ACL (NACL)?
25. What is an Elastic IP?
26. Public IP vs Private IP?
27. What is EBS?
28. EBS vs Instance Store?
29. What is an EBS Snapshot?
30. How do you connect to an EC2 instance?
31. How do you deploy a Node.js application on EC2?
32. How do you keep a Node.js application running after SSH logout?
33. What is PM2?
34. How do you configure Nginx with EC2?
35. How do you attach an EBS volume?
36. How do you increase EC2 storage?
37. What happens when an EC2 instance is stopped?
38. Stop vs Terminate vs Reboot?
39. How do you create an AMI from EC2?
40. Launch Template vs AMI?

## 3. S3
41. What is Amazon S3?
42. What is an S3 bucket?
43. S3 Bucket vs Object?
44. What is an S3 object?
45. What is an S3 Bucket Policy?
46. IAM Policy vs Bucket Policy?
47. How do you upload files to S3 using Node.js?
48. How can an S3 object be made publicly accessible, and why is that often avoided?
49. What is a pre-signed URL?
50. Why use pre-signed URLs?
51. What is S3 Versioning?
52. What is an S3 Lifecycle Policy?
53. What are S3 Storage Classes?
54. S3 Standard vs S3 Glacier storage classes?
55. How do you secure an S3 bucket?
56. What is S3 Static Website Hosting?
57. What is S3 CORS?
58. How do you store user profile images in S3?

## 4. VPC and Networking
59. What is a VPC?
60. Why do we need a VPC?
61. What is a subnet?
62. Public Subnet vs Private Subnet?
63. What is an Internet Gateway?
64. What is a NAT Gateway?
65. Internet Gateway vs NAT Gateway?
66. What is a route table?
67. What is CIDR notation?
68. What is VPC Peering?
69. What is a Security Group?
70. Security Group vs NACL?
71. What is a private IP address?
72. What is a public IP address?
73. How can an EC2 instance in a private subnet access the internet?
74. Why are databases usually placed in private subnets?
75. How would you design a VPC for a production application?

## 5. Load Balancing
76. What is a load balancer?
77. Why do we need a load balancer?
78. What is Elastic Load Balancing (ELB)?
79. Application Load Balancer (ALB) vs Network Load Balancer (NLB)?
80. What is a target group?
81. What is a listener?
82. What is a health check?
83. How does an ALB route requests?
84. How do you deploy multiple Node.js servers behind an ALB?
85. What is a sticky session?
86. How does SSL/TLS work with an ALB?
87. What is an Application Load Balancer?

## 6. Auto Scaling
88. What is Auto Scaling?
89. What is an Auto Scaling Group (ASG)?
90. Why use Auto Scaling?
91. What is a Launch Template?
92. What is a scaling policy?
93. Scale Up vs Scale Out?
94. What is horizontal scaling?
95. What is vertical scaling?
96. How does an ASG work with an ALB?
97. How would you handle sudden traffic spikes?

## 7. RDS and Relational Databases
98. What is Amazon RDS?
99. Which database engines does RDS support?
100. RDS vs running a database on EC2?
101. What is Multi-AZ deployment?
102. What is a Read Replica?
103. Multi-AZ vs Read Replica?
104. What are RDS automated backups?
105. What is a database snapshot?
106. How do you secure RDS?
107. Why keep RDS in a private subnet?
108. How does an application connect to RDS?
109. What is Amazon Aurora?
110. RDS vs Aurora?

## 8. DynamoDB
111. What is Amazon DynamoDB?
112. DynamoDB vs MongoDB?
113. What is a partition key?
114. What is a sort key?
115. What is a Global Secondary Index (GSI)?
116. What is a Local Secondary Index (LSI)?
117. What is DynamoDB provisioned capacity?
118. What is on-demand capacity?
119. What are DynamoDB Streams?
120. When would you choose DynamoDB over MongoDB?

## 9. AWS Lambda
121. What is AWS Lambda?
122. Why use Lambda?
123. What is serverless computing?
124. Lambda vs EC2?
125. What can trigger a Lambda function?
126. What is a Lambda cold start?
127. How can you reduce cold-start impact?
128. What is a Lambda timeout?
129. What are Lambda environment variables?
130. How do you give Lambda access to S3 securely?
131. How does Lambda work with API Gateway?
132. How does Lambda work with SQS?
133. What is Lambda concurrency?
134. What is Provisioned Concurrency?

## 10. API Gateway
135. What is Amazon API Gateway?
136. API Gateway vs ALB?
137. How does API Gateway work with Lambda?
138. What is an API, and what is a REST API?
139. API Gateway REST API vs HTTP API?
140. How do you secure API Gateway?
141. How can authentication be implemented for API Gateway?
142. What is API throttling?
143. How do you handle CORS in API Gateway?

## 11. CloudFront
144. What is Amazon CloudFront?
145. Why use CloudFront?
146. What is a CDN?
147. CloudFront vs S3?
148. How does CloudFront improve performance?
149. What is a CloudFront distribution?
150. What is a CloudFront origin?
151. What is CloudFront caching?
152. How do you invalidate CloudFront cache?
153. How do CloudFront and S3 work together?

## 12. Route 53 and DNS
154. What is Amazon Route 53?
155. What is DNS?
156. What is a hosted zone?
157. What is an A record?
158. What is a CNAME record?
159. A Record vs CNAME?
160. What is an Alias record?
161. What are DNS routing policies?
162. Simple Routing vs Weighted Routing?
163. What is Failover Routing?
164. How do you connect a domain to an EC2 server?
165. How do you connect a domain to an ALB?

## 13. CloudWatch
166. What is Amazon CloudWatch?
167. What are CloudWatch Metrics?
168. What are CloudWatch Logs?
169. What is a CloudWatch Alarm?
170. How do you monitor EC2?
171. How do you monitor CPU utilization?
172. How do you monitor application logs?
173. CloudWatch vs CloudTrail?
174. How can CloudWatch trigger an alert?

## 14. CloudTrail
175. What is AWS CloudTrail?
176. Why do we use CloudTrail?
177. CloudWatch vs CloudTrail?
178. What information can CloudTrail record?
179. How can you investigate who changed an AWS resource?

## 15. SQS and SNS
180. What is Amazon SQS?
181. Why use SQS?
182. What is a queue?
183. Standard Queue vs FIFO Queue?
184. What is Visibility Timeout?
185. What is a Dead-Letter Queue (DLQ)?
186. What is Amazon SNS?
187. SNS vs SQS?
188. How can SNS and SQS work together?
189. How would you process background jobs using SQS in Node.js?

## 16. ECS and Containers
190. What is Amazon ECS?
191. ECS vs EC2?
192. ECS vs Lambda?
193. What is an ECS cluster?
194. What is an ECS task?
195. What is an ECS service?
196. What is AWS Fargate?
197. Fargate vs ECS on EC2?
198. How do you deploy a Dockerized Node.js application to ECS?
199. How does ECS work with an ALB?
200. ECS vs Kubernetes/EKS?

## 17. ECR
201. What is Amazon ECR?
202. Why use ECR?
203. ECR vs Docker Hub?
204. How do you push a Docker image to ECR?
205. How does ECS pull an image from ECR?

## 18. EKS and Kubernetes
206. What is Amazon EKS?
207. EKS vs ECS?
208. Why use Kubernetes on AWS?
209. What is an EKS cluster?
210. What is a node group?
211. EKS vs self-managed Kubernetes?
212. How do you deploy a Node.js application on EKS?

## 19. CI/CD and DevOps
213. What is CI/CD?
214. What is AWS CodePipeline?
215. What is AWS CodeBuild?
216. What is AWS CodeDeploy?
217. CodeBuild vs CodeDeploy?
218. How does CodePipeline work?
219. How would you configure GitHub Actions with AWS?
220. How would you build a Docker-to-AWS CI/CD pipeline?
221. How do you automate Node.js application deployment?
222. What is Blue-Green Deployment?
223. What is Rolling Deployment?
224. Blue-Green vs Rolling Deployment?

## 20. Security and Secrets
225. What is AWS Secrets Manager?
226. Secrets Manager vs environment variables?
227. What is AWS Systems Manager Parameter Store?
228. Secrets Manager vs Parameter Store?
229. How do you securely store MongoDB credentials?
230. How do you securely store JWT secrets?
231. Why should AWS access keys never be hardcoded?
232. What is AWS KMS?
233. What is encryption at rest?
234. What is encryption in transit?
