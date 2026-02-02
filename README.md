# system-design
<h1>1. Scalability</h1>
<b>Scalability is ability of system to handle increased load by adding resources</b>

need to understand of scalability mesuerment 
<ol>
  <li>Request Per Second (RPS) : how many api request per second (100000 RPS)</li>
  <li>Active Cuncurrent User  : how many user active at same time (50000 Cuncurrent User)</li>
  <li>Data Volume : data size we are going to store or process (10 TB)</li>
  <li>Throughput : amount of data per second (1 GB)</li>
  <li>Query Per Second : database query per second (1000000 QPS)</li>
</ol>


<h1> Type of scaling </h1>
<b>1. Vertical Scaling (Scale Up)</b>
<img width="1559" height="810" alt="Screenshot from 2026-01-26 20-43-23" src="https://github.com/user-attachments/assets/e6ca9f58-a6d6-4d8b-9647-314707f5721f" />
Vertical Scaling is about adding more resource to machine (server) if server has 8 cpu 16 ram add 16 cpu 32GB RAM faster SSD and good network card for better network bandwidth 
Vartcial Scaling hit ceiling when available biggest machine is not big enough to handle load 
</hr>

<b>2 Horizontal Scaling (Scale Out)</b>
<img width="1559" height="810" alt="Screenshot from 2026-01-26 20-49-31" src="https://github.com/user-attachments/assets/0b1b258d-9eaf-45d9-8879-c06db8590d3c" />

Horizontal scaling is about adding more servers instead of adding more resources in single server and load balancer, load balancer is a system who is responsible for distributing incomeing request to multiple servers so no single server become overloaded by requests.

<h3> Factor for measuring scalability</h3><br/>
 1.QPS : query per second <br/>
 2.Active concurrent users <br/>
 3.Data volume, amount of data is prosessed or store <br/>
 4. Bandwidth, amount of data per unit <br/> 
5. message process queues per second <br/>
6. RPS : request per second <br/>

