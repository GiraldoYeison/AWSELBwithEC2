# AWSELBwithEC2
Setting up Load Balancers with EC2 

# AWSELBwithEC2
Setting up Load Balancers with EC2 in us-east-2

<h1>Setting up Load Balancers with EC2</h1>
<div><b>Creation Date:</b> October 21, 2023</div>
<div><b>Created By:</b> Yeison Giraldo</div>

<div style="height: 24px">&#8203;</div>
<hr />
<div style="height: 24px">&#8203;</div>


<div><h2><a href="https://us-east-2.console.aws.amazon.com/ec2/home?region=us-east-2#LoadBalancers:"># Load balancers | EC2 | us-east-2</a></h2></div>

<div><h3>1. Click on EC2…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f1651082-d68c-469b-be89-2e94b84ec16b/b522c0dd-b1e0-4be0-87d1-add9e6f34a79.png?fm=png&crop=focalpoint&fit=crop&fp-x=0.3976&fp-y=0.2043&fp-z=2.2705&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=409&mark-y=322&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zODMmaD0xMDcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on EC2…" />
</div>

<div><h3>2. Click on Load Balancers</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/84e75be8-5819-401b-a357-26a3e0e47190/165522e1-2cc4-4691-8599-b9e1bbb244d8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0588&fp-y=0.7996&fp-z=2.6587&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=66&mark-y=374&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNDMmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Load Balancers" />
</div>

<div><h3>3. Click on Create load balancer</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/98334991-fa59-48d2-88e0-7d5c82fdc64a/5dfc18bc-1538-441a-9eb0-62a9938343b7.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8688&fp-y=0.1435&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=511&mark-y=286&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00NjImaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create load balancer" />
</div>

<div><h3>4. Click on Create</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/640b92a2-5e42-4ca7-848e-fd1ff766dcab/3e6bcbc8-1dec-4d1c-9b90-e97f109c8504.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1057&fp-y=0.7612&fp-z=2.7065&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=230&mark-y=357&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMjYmaD05NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create" />
</div>

<div><h3>5. Type "web-elb"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/57535848-7378-434c-9040-1d454f3bdc2d/cef4d293-d0db-4a4e-b1c6-279d05660a1f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.4962&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=385&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD00MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;web-elb&quot;" />
</div>

<div><h3>6. Click on -…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/59cfc35a-6aeb-4d19-81da-7969ddbc0116/d6d5a646-1424-4307-b13c-709017c5d84a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.4491&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=369&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD03MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on -…" />
</div>

<div><h3>7. Check us-east-2a (use2-az1)</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/37028fb8-9612-456c-a106-68112d121486/0def579e-d4d0-45c2-ab55-4d74310a95ab.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0880&fp-y=0.6079&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=296&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check us-east-2a (use2-az1)" />
</div>

<div><h3>8. Check us-east-2b (use2-az2)</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/314498ff-b3ba-4cdf-a0b9-423f57d86af4/bdeea44c-932b-4d1a-a7df-1329e09e3e38.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0880&fp-y=0.8653&fp-z=3.1620&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=303&mark-y=434&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MiZoPTYyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check us-east-2b (use2-az2)" />
</div>

<div><h3>9. Click on Select up to 5 security groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/ba322f0d-e09e-474f-9bea-89a4d4b4dadf/f4b05d5a-f703-4d1f-b8bc-960ff4329c78.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.4830&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=385&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD00MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select up to 5 security groups" />
</div>

<div><h3>10. Click on create a new security group </h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/cf1071c2-bf5d-43d6-a4b8-c8b5e3ae8f44/36594d1e-0f2d-427c-a833-5e953b7356a6.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.6582&fp-y=0.3872&fp-z=2.4555&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=407&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zODUmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on create a new security group " />
</div>

<div><h3>11. Drag highlighted input</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/52451fec-2985-4e05-b5b2-6609d0ebbc52/217f5310-ab9a-4769-a745-9e8a5693065e.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2753&fp-y=0.3373&fp-z=1.3023&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=65&mark-y=333&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MzEmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Drag highlighted input" />
</div>

<div><h3>12. Copy input titled "web-elb-sg"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/8e6b410f-4476-4eb2-a4aa-ef7794880d51/e345929b-a369-4d78-a0c9-9b222b2fa8fe.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2753&fp-y=0.3373&fp-z=1.3023&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=65&mark-y=333&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MzEmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Copy input titled &quot;web-elb-sg&quot;" />
</div>

<div><h3>13. Click on Description Info</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/fbc7d2fc-4990-4b4d-8305-78385fda7106/c95f1e8c-8e3a-4e27-91db-2cb8a4233641.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2753&fp-y=0.4447&fp-z=1.3023&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=65&mark-y=382&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MzEmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Description Info" />
</div>

<div><h3>14. Paste input</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/cabd8851-79fb-400f-873d-308f815f9c9c/bbf11786-6b88-4103-b48b-d1cf7ceb1f5b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2753&fp-y=0.4447&fp-z=1.3023&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=65&mark-y=382&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MzEmaD00NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Paste input" />
</div>

<div><h3>15. Click on Add rule</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/0c38a09c-ce7e-4b31-b970-605df68b4eab/eade1be8-5451-416c-94df-1c8607325bff.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0813&fp-y=0.5422&fp-z=2.6328&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=131&mark-y=358&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNTImaD05MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Add rule" />
</div>

<div><h3>16. Click on Custom TCP</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/8dd933fc-4a65-4dd9-ad05-d0b72f764e90/095ca9be-a171-4393-916a-0143ac42bd05.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1105&fp-y=0.5268&fp-z=2.2820&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=113&mark-y=364&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzgmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Custom TCP" />
</div>

<div><h3>17. Click on Custom TCP…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/35a0814d-2d93-4c02-a615-68ba4cf081f2/dd490769-ed27-4cd0-81c0-ab833592c1cd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1105&fp-y=0.1369&fp-z=2.2820&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=113&mark-y=213&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzgmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Custom TCP…" />
</div>

<div><h3>18. Type "80"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/d380362d-64d4-42fe-bc1c-b1eb70f0dec1/231e7c73-beef-48f2-86fc-c9f079347d2a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3315&fp-y=0.5268&fp-z=2.2820&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=411&mark-y=364&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzgmaD04MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;80&quot;" />
</div>

<div><h3>19. Click on Custom</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3e12e24e-eebe-4897-a9f4-4eb1cde47544/326cf278-b830-427d-bfc4-a895c90752f5.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4420&fp-y=0.5268&fp-z=2.7394&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=356&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTQmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Custom" />
</div>

<div><h3>20. Click on dropdown trigger</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/33d25bdd-dedf-4334-ba7f-4cd549506da2/a4efb297-2566-44fe-80e5-16dc3c7d9e06.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5525&fp-y=0.5257&fp-z=2.2820&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=411&mark-y=366&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzgmaD03NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on dropdown trigger" />
</div>

<div><h3>21. Click on 0.0.0.0/0</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/8302083b-b9a7-4b5a-bb4f-344900fd52c1/c722e773-7eaf-4e46-b644-d04dd1b3e9aa.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5462&fp-y=0.1610&fp-z=2.3494&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=423&mark-y=267&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNTQmaD03OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on 0.0.0.0/0" />
</div>

<div><h3>22. Click on Create security group</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/d176d5ad-111f-475c-9351-710aa8b678f0/ad4dec6a-1448-4546-9573-8baf1b8b647f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8585&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=251&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTkmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create security group" />
</div>

<div><h3>23. Click on Refresh Security groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/b5f82e96-51f2-4c14-91d6-2ebcb27c1630/dab3fcf3-42ea-422d-80d1-93acb422c59a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.6800&fp-y=0.4830&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=525&mark-y=353&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNTAmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Refresh Security groups" />
</div>

<div><h3>24. Click on Select up to 5 security groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/42e6a58b-07de-41a2-be0a-055389be940c/62f02073-1785-4acd-9d75-0c1d7eb46f41.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.4830&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=385&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD00MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select up to 5 security groups" />
</div>

<div><h3>25. Click on default…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/94adac04-58d6-4e0c-b4f6-c7cc2c93ebbc/aad0c7ae-05d2-4d0d-a92b-ba7d5a9f020a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.6637&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=472&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD01NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on default…" />
</div>

<div><h3>26. Click on Create Application Load BalancerInfo…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/910b0a63-0735-477d-9dca-66cacdc6be43/8c344244-998e-4217-ae6b-dcd94aca66d9.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4937&fp-y=0.4124&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=32&mark-y=-1157&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMTIxJmg9Mjk4MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create Application Load BalancerInfo…" />
</div>

<div><h3>27. Click on Security groups…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/bcb04330-65e2-4e70-b1c0-5bff1347688a/86ca93d3-35d9-495c-99d1-f05f0395bafd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4582&fp-y=0.5104&fp-z=1.0595&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=71&mark-y=323&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMDIyJmg9MTY0JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Security groups…" />
</div>

<div><h3>28. Click on highlight</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/defabf89-42a6-4acd-a780-b8cd4e6081c5/b693c726-e559-43db-992d-7f892f89f8fd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7520&fp-y=0.5159&fp-z=2.4418&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=326&mark-y=297&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01NDgmaD0yMTcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on highlight" />
</div>

<div><h3>29. Click on web-elb-sg…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/abde64b4-219f-4af4-b152-da79448c4518/f61e7895-a3fb-4d35-8def-4544f7bb29a6.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.5608&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=377&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD01NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on web-elb-sg…" />
</div>

<div><h3>30. Click on Create Application Load BalancerInfo…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/4dc76bf5-0014-4e32-aaa7-bd252b28b47c/129f566f-c557-4346-91a2-fafcd1900543.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4937&fp-y=0.4124&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=32&mark-y=-1157&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMTIxJmg9Mjk4MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create Application Load BalancerInfo…" />
</div>

<div><h3>31. Click on Select up to 5 security groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3eb2b9dd-856a-4882-8389-76864ff81083/5e29c611-f9ea-4a88-ac5c-5bdff35142b8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3603&fp-y=0.2640&fp-z=1.1380&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=97&mark-y=223&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTAmaD00MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select up to 5 security groups" />
</div>

<div><h3>32. Click on Listeners and routing</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/5d6464df-05e7-4cd0-8970-d0b305f6849d/b3b4857d-fff2-4cc0-880f-ad3808fdaa6d.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1404&fp-y=0.3286&fp-z=2.2782&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=194&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zODAmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Listeners and routing" />
</div>

<div><h3>33. Click on ListenerHTTP:80</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/df4c83a8-8920-4b59-aafb-34c65a3607e5/4ba7d075-4248-424d-b8a5-e8d424175656.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4582&fp-y=0.6254&fp-z=1.0938&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=111&mark-y=362&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz05NzgmaD0yMzMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on ListenerHTTP:80" />
</div>

<div><h3>34. Click on Create target group </h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/957059a8-8b7f-4b2e-8128-7a9bbc180d2b/07e8d38a-431e-4fbf-869d-e0772ba7aeaf.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3936&fp-y=0.5893&fp-z=2.4208&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=436&mark-y=377&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMjkmaD01NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create target group " />
</div>

<div><h3>35. Type "web-servers-target-group"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f07a930d-3d1b-42c5-ad31-2a8c78bb1d49/890a0be9-4bf3-4618-9a02-00fa1aebd242.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4897&fp-y=0.6177&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=248&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03MDQmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;web-servers-target-group&quot;" />
</div>

<div><h3>36. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/8d9a4ab2-05ad-4d32-865e-cbe521d7868e/25350958-16f2-4066-9501-479f72d5ffb5.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTEmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>37. Click on Create target group</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/88104f77-e971-4bad-8315-c4c9cebbe241/033806e8-c886-420f-b64d-5e9632e41e4e.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8928&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=359&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NTMmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create target group" />
</div>

<div><h3>38. Check on</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3a1cfe39-72b7-4788-9b62-1479830de944/254a7b75-9f52-46b9-bb14-6ca8eaae9e83.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2269&fp-y=0.3571&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check on" />
</div>

<div><h3>39. Click on Targets</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/2aae42c4-3105-4de5-9e63-7fa13a245237/bb2a6578-7ccb-418a-b41a-5c2fdd822202.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3064&fp-y=0.6073&fp-z=2.6797&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=482&mark-y=330&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMzUmaD0xNTAmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Targets" />
</div>

<div><h3>40. Click on Monitoring</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/cde3a98c-bc58-4b2a-9441-01f34b9c01df/c132fc85-89fb-4ae0-bb2f-8df011bdbdcf.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3821&fp-y=0.5986&fp-z=2.5533&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=460&mark-y=334&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yODEmaD0xNDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Monitoring" />
</div>

<div><h3>41. Click on Auto Scaling Groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/0c3142e4-9d1d-43bd-b8b3-67302b2e64ae/8790ceaf-f7ea-4b29-8603-dede3b597187.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0713&fp-y=0.9102&fp-z=2.4922&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=62&mark-y=600&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMDMmaD01NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Auto Scaling Groups" />
</div>

<div><h3>42. Click on Create Auto Scaling group</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/ee479715-0b6e-4e4e-836d-5fcda00a7a2c/0ad8e982-803a-47a0-a2ed-7f497df1c191.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7535&fp-y=0.2563&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=305&mark-y=353&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01OTEmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create Auto Scaling group" />
</div>

<div><h3>43. Type "web-server-asg"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/23a4d274-34f6-4174-b227-f35c333c54bc/b687d204-6882-4716-9e83-d20f4c1c14ee.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5137&fp-y=0.3790&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=208&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03ODQmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;web-server-asg&quot;" />
</div>

<div><h3>44. Click on Create a launch template </h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/368fe7a0-fb69-4e19-bc66-56862149c8df/d02d817d-d0df-42fa-b672-3a6406490015.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3470&fp-y=0.6616&fp-z=2.2820&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=411&mark-y=379&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzgmaD01MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create a launch template " />
</div>

<div><h3>45. Type "WebServerLaunchTemplate"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/1b9e35d8-bac9-47e1-aa66-9f433d9c8208/18f2ca45-7db2-404e-ab30-b3d3a6cb72d8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2761&fp-y=0.3724&fp-z=1.4081&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=120&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTMmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;WebServerLaunchTemplate&quot;" />
</div>

<div><h3>46. Type "Ver.1"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/a9808f99-d483-448e-b818-d92e795d9cbe/4af562ec-aed3-458b-8d39-8af73ad22df3.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2761&fp-y=0.4797&fp-z=1.4081&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=120&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTMmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;Ver.1&quot;" />
</div>

<div><h3>47. Click on Amazon Linux</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f9f4decd-3cfb-4723-830f-525ced355a23/e507519f-9e0c-42e3-b4d8-4aee5cea33c8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1116&fp-y=0.3614&fp-z=2.2383&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=201&mark-y=272&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xOTkmaD0yNjYmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Amazon Linux" />
</div>

<div><h3>48. Click on Don't include in launch template</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/4b00726c-31b7-4a2e-8624-a0f5cb5d0d29/2f683df4-96c5-4201-ae2a-2cdac7e8601b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2727&fp-y=0.7010&fp-z=1.4214&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=121&mark-y=440&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02ODgmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Don&#039;t include in launch template" />
</div>

<div><h3>49. Click on t2.micro…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/1b58b61c-fda3-4c87-9a5b-2e556e877c6c/865aa0ee-fee9-45e3-b44f-c33002dc6021.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2664&fp-y=0.3231&fp-z=1.4472&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=123&mark-y=302&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NzkmaD0xNTQmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on t2.micro…" />
</div>

<div><h3>50. Click on Don't include in launch template</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/4de85d55-be50-4706-8788-1ee6eb306168/e7fb303e-f33f-4c53-917e-9f17ec3a80d2.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2727&fp-y=0.6451&fp-z=1.4214&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=121&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02ODgmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Don&#039;t include in launch template" />
</div>

<div><h3>51. Click on Select security groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/95d0162c-0029-4cc1-967c-c65ab2fba171/b750f9a2-c844-411f-ac3e-166d172bcc64.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2727&fp-y=0.8412&fp-z=1.4214&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=121&mark-y=602&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02ODgmaD01MCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select security groups" />
</div>

<div><h3>52. Click on web-elb-sg…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/4b6abbb4-9155-41d1-b7a2-420874001a48/41f5a0c4-19ef-4ee8-a46c-79aef475bbc8.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2727&fp-y=0.6407&fp-z=1.4214&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=121&mark-y=370&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02ODgmaD03MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on web-elb-sg…" />
</div>

<div><h3>53. Click on Advanced details Info</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/b5739b6f-ee99-42d8-9ee6-3d7faee6853c/1a712553-9da2-424c-95b3-df8cbbb40fd4.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3463&fp-y=0.9080&fp-z=1.1361&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=77&mark-y=689&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03OTEmaD03MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Advanced details Info" />
</div>

<div><h3>54. Click on User data - optional  Info</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/d8c9d921-4f51-4712-8476-f53b955eb561/985986f3-a0f7-4ae0-91d2-4987fe3e032a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2761&fp-y=0.6900&fp-z=1.4081&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=120&mark-y=239&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTMmaD00MzUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on User data - optional  Info" />
</div>

<div><h3>55. Click on User data - optional  Info</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/7271030b-93cc-453d-a214-49f40c041ec3/77bdb274-69d9-4327-8278-537ec908b1d1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2761&fp-y=0.6900&fp-z=1.4081&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=120&mark-y=239&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTMmaD00MzUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on User data - optional  Info" />
</div>

<div><h3>56. Paste text area</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/257e4d1e-e8c6-4ec0-86c8-d4dfaed3f788/6bb18fa2-1a89-4c98-938e-0c3740f739e1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2761&fp-y=0.6900&fp-z=1.4081&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=120&mark-y=239&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTMmaD00MzUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Paste text area" />
</div>

<div><h3>57. Click on Create launch template</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/28b44a8a-c774-482e-8220-b7b99e1339ab/e3cbcf95-09d6-45e8-8b16-14ec8f73f44d.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8381&fp-y=0.7547&fp-z=3.7418&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=252&mark-y=339&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02OTcmaD0xMzMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create launch template" />
</div>

<div><h3>58. Click on Refresh Launch template</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/6cff0111-d40a-41b4-a69e-44a056b9d623/73d4f2a5-27cb-4d3d-97e1-e53ef1f8e997.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7797&fp-y=0.6276&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=525&mark-y=353&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNTAmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Refresh Launch template" />
</div>

<div><h3>59. Click on Select a launch template</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/a7a6bebd-2ede-43f2-a9a0-c49a9a704fc1/95466cf9-9bd9-476b-a29c-4a0f08607e26.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5137&fp-y=0.6276&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=208&mark-y=380&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03ODQmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select a launch template" />
</div>

<div><h3>60. Click on WebServerLaunchTemplate…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/657c84f6-2d5d-4d73-8248-cf30b14c45e3/b409cfd5-2a82-4a78-a8e4-b865a257e8ec.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5137&fp-y=0.6988&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=208&mark-y=446&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz03ODQmaD01MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on WebServerLaunchTemplate…" />
</div>

<div><h3>61. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/ea3c12a9-e3d2-4a01-bbf6-99f0332505fb/73506a6a-1ed7-4767-b98c-b92e537951d4.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTEmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>62. Click on Select Availability Zones and subnets</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/17f388b1-2b56-457f-802a-cc8d4af6df61/a9a75a85-8928-445d-ad32-6a1c2f5dcbd1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4176&fp-y=0.8193&fp-z=1.7260&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=311&mark-y=527&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01NzkmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select Availability Zones and subnets" />
</div>

<div><h3>63. Click on us-east-2b | subnet-0f8425b73f42ca440…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/ea98940e-8177-4ac0-97e0-43f48fde50bc/52e885c0-9af7-4aa0-81f1-5c2f2dce4356.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4176&fp-y=0.7218&fp-z=1.7260&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=311&mark-y=378&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01NzkmaD04NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on us-east-2b | subnet-0f8425b73f42ca440…" />
</div>

<div><h3>64. Click on Step 1…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/bc9741ed-a2bf-4ae1-b24a-5d2cc0cd024b/c986fae4-67f7-48c2-929f-368c7aad4192.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4937&fp-y=0.5312&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=32&mark-y=-25&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMTIxJmg9OTEwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Step 1…" />
</div>

<div><h3>65. Click on Select Availability Zones and subnets</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/d09d2e82-3239-4116-be6f-f943c67e8053/797d9b82-1084-4d14-a4ce-e8e96eaf5d80.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4176&fp-y=0.8193&fp-z=1.7260&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=311&mark-y=527&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01NzkmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select Availability Zones and subnets" />
</div>

<div><h3>66. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/1a3fad15-0b6d-4274-a284-0193c0e9c08b/f537bb03-aaa7-471a-8e37-2200ee809a4f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTEmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>67. Select Attach to an existing load balancer</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/fa0649fb-7ca8-4c76-a0ba-3948201001c7/9ce13162-b587-4f6a-aef7-900b218b2700.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4908&fp-y=0.4140&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Select Attach to an existing load balancer" />
</div>

<div><h3>68. Click on Select target groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/26a1dab1-92bd-4db9-91c3-c16cf3c7a121/32629a53-179d-4894-bcc9-e71335f6e75c.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5377&fp-y=0.8160&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=168&mark-y=579&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NjMmaD00OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Select target groups" />
</div>

<div><h3>69. Click on web-servers-target-group | HTTP…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/52ab5a2c-5fcc-494a-9bba-c09a67dd773e/ca843b4b-c5ee-43b8-9132-12a19fe40226.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5377&fp-y=0.7711&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=168&mark-y=517&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NjMmaD03MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on web-servers-target-group | HTTP…" />
</div>

<div><h3>70. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3a4cc35a-49f0-4793-982e-e4eb71869346/82de62cf-6f29-45fc-a7aa-5893b237579a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTEmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>71. Type "2"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3897a377-e5b5-4e2d-9f22-87d2b2e9231e/f929b923-210e-4ca8-9371-d3303b91eaaf.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3104&fp-y=0.3636&fp-z=2.7394&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=356&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTQmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;2&quot;" />
</div>

<div><h3>72. Type "2"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/0a26cb20-288d-4c7c-9db8-cff6ca886974/04d2bde4-afc7-42ac-a8cb-09b64bb17178.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3104&fp-y=0.4491&fp-z=2.7394&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=356&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTQmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;2&quot;" />
</div>

<div><h3>73. Type "6"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/c01ada85-b835-4dcf-a807-072de951dc07/cf876710-63d2-4b48-ba67-0a19d1699c73.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3104&fp-y=0.5345&fp-z=2.7394&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=356&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTQmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;6&quot;" />
</div>

<div><h3>74. Select Target tracking scaling policy</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f8f4e631-6ac8-4009-86f2-5a264bc1b98b/bb473115-5186-4868-a95a-cdb5dff4d7d5.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.2986&fp-y=0.5838&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Select Target tracking scaling policy" />
</div>

<div><h3>75. Type "0"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/874ecfb1-8279-4155-980e-16e477854f39/07c48810-8867-443c-a08d-143c286af9de.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3104&fp-y=0.6977&fp-z=2.7394&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=493&mark-y=356&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTQmaD05NyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;0&quot;" />
</div>

<div><h3>76. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/99aed2c5-3274-4630-be71-6bc841fa25f8/ebf322f9-315e-40df-aeae-3e8c229b823c.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.9266&fp-z=4.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=455&mark-y=501&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTEmaD0xNDImZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>77. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/1e153658-75da-436d-87f4-4b37b1088554/9c06ba7b-fd98-4146-a25f-4e5927d6dfc4.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.3012&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=501&mark-y=353&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTImaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>78. Click on Add tag…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f1953915-3382-4e9d-9609-2095b3a055d6/c6668368-913e-4e0f-b42d-a749584b3ffd.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5617&fp-y=0.5038&fp-z=1.3849&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=128&mark-y=368&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz05NDMmaD03NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Add tag…" />
</div>

<div><h3>79. Click on Add tag</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/9f6eda38-2459-4a0c-8738-da2f72016d46/25ff30a3-98ff-4fa7-945d-019b4fded28e.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3160&fp-y=0.4929&fp-z=2.6587&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=479&mark-y=358&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNDMmaD05NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Add tag" />
</div>

<div><h3>80. Type "Name"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/19ece3c0-eb17-4732-9fac-c09e92c1b359/c7982487-9c70-4dc4-ac69-d0ae3b28590a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3455&fp-y=0.4995&fp-z=2.2975&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=414&mark-y=364&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzMmaD04MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;Name&quot;" />
</div>

<div><h3>81. Type "auto-webserver"</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/311a154e-e167-4d3a-8924-fbe012be94f0/0af13d37-3af1-4e1a-817a-b0eb6875eba5.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.4897&fp-y=0.4995&fp-z=2.2975&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=414&mark-y=364&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zNzMmaD04MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Type &quot;auto-webserver&quot;" />
</div>

<div><h3>82. Click on Next</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/48ca1771-f72e-4737-a68d-7b478098614f/daf4c489-d037-418d-b330-4bbedadbe3df.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8300&fp-y=0.6572&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=501&mark-y=353&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMTImaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Next" />
</div>

<div><h3>83. Click on Create Auto Scaling group</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f123fa8a-f922-4425-a8ed-9ec21796a67c/2f7e744b-0ecc-4c73-8862-6a7db3f1f4cc.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7757&fp-y=0.9266&fp-z=3.2368&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=271&mark-y=560&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02NTcmaD0xMTUmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Create Auto Scaling group" />
</div>

<div><h3>84. Click on Refresh Auto Scaling groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/85869710-4d9b-4df5-8d5d-0520b679d755/72124a0d-2807-46a2-a3ff-c74fe322e384.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3585&fp-y=0.1435&fp-z=2.9086&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=525&mark-y=286&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNTAmaD0xMDMmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Refresh Auto Scaling groups" />
</div>

<div><h3>85. Click on EC2</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/5f22aaec-7ce6-4b59-9e2d-ad7f84117de5/ca6b15b3-a2f1-4fab-b135-a7f6c33d1973.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0680&fp-y=0.0789&fp-z=3.0043&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=203&mark-y=152&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04NSZoPTgwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on EC2" />
</div>

<div><h3>86. Click on Instances (running)…</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/20682f8f-23ab-4a4d-af2f-b8de1058b958/c1b51ef0-ffb7-4dd3-8f81-ce6daf3b3494.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3367&fp-y=0.2081&fp-z=1.8665&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=336&mark-y=275&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz01MjgmaD03OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instances (running)…" />
</div>

<div><h3>87. Click on Refresh instances</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/def39202-db6c-473b-9201-17b8a8453fdc/be60eea3-e401-4fd9-bf38-718b651feaad.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5403&fp-y=0.0712&fp-z=2.9166&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=525&mark-y=122&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNTAmaD05MyZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Refresh instances" />
</div>

<div><h3>88. Check on</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/f70e3c27-9251-4b98-bf3f-46d2b68b5053/79779cc8-5d5f-4222-ab43-bff9a28cdf23.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1973&fp-y=0.2727&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check on" />
</div>

<div><h3>89. Check on</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/4f23974a-52aa-4985-a74c-f334fa310808/32f017b4-1699-47fe-a904-39164dbc195b.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1973&fp-y=0.2366&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check on" />
</div>

<div><h3>90. Uncheck on</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/c28a3771-4279-42c7-9188-5625657b6eff/b5784328-bd90-426e-b33d-2fbdd49b8699.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1973&fp-y=0.2727&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Uncheck on" />
</div>

<div><h3>91. Click on Load Balancers</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/09e1f025-5f16-4585-b33a-84b5486989d3/ba7de642-161b-4cde-9b1e-1c4997d41333.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0588&fp-y=0.7974&fp-z=2.6587&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=66&mark-y=374&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNDMmaD02MSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Load Balancers" />
</div>

<div><h3>92. Click on Copy DNS name of load balancer web-elb to clipboard</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/a6a6b03d-2683-4be8-acd6-386c77dcd065/14b7a8e4-98a9-4472-8ccc-c662c8a1a181.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.6046&fp-y=0.8916&fp-z=3.0897&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=556&mark-y=497&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz04OCZoPTgyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Copy DNS name of load balancer web-elb to clipboard" />
</div>

<div><h3>93. Copy text</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/12eb7504-eb80-4f2f-a5ce-e0b96172ab40/7bd756e6-c3cf-4450-a7dd-4147ebcc5beb.jpg?fm=png&q=100&crop=focalpoint&fit=crop&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Copy text" />
</div>

<div><h2><a href="http://web-elb-447842548.us-east-2.elb.amazonaws.com/"># web-elb-447842548.us-east-2.elb.amazonaws.com</a></h2></div>

<div><h3>94. Click on highlight</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/97b3a03d-c84c-4205-aecd-68f5668c3d7f/1c10b0d9-3444-45d8-83f1-8e08861ab0ee.jpg?fm=png&q=100&crop=focalpoint&fit=crop&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on highlight" />
</div>

<div><h3>95. Click on highlight</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/2ffa2235-fff0-4e88-aabd-901965598b29/4ab9e7d4-7dd3-4c74-a6c5-738a72d8c0ca.jpg?fm=png&q=100&crop=focalpoint&fit=crop&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on highlight" />
</div>

<div><h2><a href="https://us-east-2.console.aws.amazon.com/ec2/home?region=us-east-2#LoadBalancers:"># Load balancers | EC2 | us-east-2</a></h2></div>

<div><h3>96. Click on Target Groups</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/208272bd-4c55-46e8-932a-6a1f84bf973a/4f9f2508-ec4e-4342-9662-5527acea8eee.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0569&fp-y=0.8302&fp-z=2.6851&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=67&mark-y=410&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yMzMmaD02MiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Target Groups" />
</div>

<div><h3>97. Click on web-servers-target-group</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/5485055f-7533-4d39-81a4-05a76d023c49/a2a0205b-d2cb-4348-85eb-1b8d10d73b71.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.3082&fp-y=0.3045&fp-z=2.5060&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=451&mark-y=352&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yOTgmaD0xMDcmZml0PWNyb3AmY29ybmVyLXJhZGl1cz0xMA%3D%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on web-servers-target-group" />
</div>

<div><h3>98. Click on targets</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/16898c82-94d4-4038-a299-b4b5e91866a9/8be98084-0155-4558-bb8a-b776c1f28322.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.5824&fp-y=0.8614&fp-z=1.2563&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=30&mark-y=598&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xMTQxJmg9MTQyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on targets" />
</div>

<div><h3>99. Click on Instances</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/5c7c6fb6-3922-4d9c-af3b-7094734097f9/b5131041-5b16-4700-aab6-bbecdffbb5c1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.0455&fp-y=0.2245&fp-z=2.8611&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=71&mark-y=372&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xNzAmaD02NiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instances" />
</div>

<div><h3>100. Check on</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/352bd8b3-53ac-4df0-ab4d-25eb20160414/107cfa12-5fe7-4e42-a1e6-b59d8b1b8cf1.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.1973&fp-y=0.1884&fp-z=3.0855&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=570&mark-y=375&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz02MCZoPTYwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Check on" />
</div>

<div><h3>101. Click on Instance state</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/e0032702-1bd0-4639-91c9-59b20d498e13/f293080c-4397-4f14-a9a7-84b2baa83df7.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7010&fp-y=0.0712&fp-z=2.7782&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=397&mark-y=116&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00MDcmaD04OSZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Instance state" />
</div>

<div><h3>102. Click on Terminate instance</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/3e6a863c-a1c7-43c8-8229-111a391c777b/74d0b27f-9f2a-410e-bc69-9c1926f4333f.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.7092&fp-y=0.2399&fp-z=2.7840&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=372&mark-y=358&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz00NTcmaD05NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Terminate instance" />
</div>

<div><h3>103. Click on Terminate</h3>
<img src="https://images.tango.us/workflows/c5a235f6-f4de-40d7-9d69-326156f8b272/steps/cffebeed-5c9c-4abf-818d-6d1e6ef0f85d/d92fffdb-ea2a-4729-9464-7f105a808c0a.jpg?fm=png&q=100&crop=focalpoint&fit=crop&fp-x=0.8356&fp-y=0.6725&fp-z=2.9461&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=463&mark-y=358&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0zMTEmaD05NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw" style="border-radius: 8px; border: 1px solid #F4F2F7;" width="600" alt="Click on Terminate" />
</div>

<div><h2><a href="http://web-elb-447842548.us-east-2.elb.amazonaws.com/"># web-elb-447842548.us-east-2.elb.amazonaws.com</a></h2></div>

<br/>
<hr/>
<div>

</div>
