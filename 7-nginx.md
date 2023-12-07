# Web Server Deployment

## NGINX    

### What are some common use cases for NGINX?
- <u> Reverse Proxy:</u> Balancing and distributing incoming web traffic among multiple servers, enhancing performance and reliability.
- <u> Load Balancer:</u> Distributing incoming network or application traffic across multiple servers to optimize resource utilization and prevent overloading
### How does NGINX handle tasks that could slow down the web server?
- Efficient Event-Driven Architecture: NGINX uses an event-driven model, allowing it to handle numerous connections simultaneously without creating new threads for each connection, thus reducing resource overhead.
- Optimized Processing: NGINX employs asynchronous processing, efficiently managing tasks such as serving static content, handling concurrent connections, and managing resources, minimizing bottlenecks that could slow down the server.
- Caching Mechanisms: Utilizing caching strategies, NGINX stores frequently accessed data in memory, reducing the need for repeated requests to the web server, thereby enhancing performance.

### Describe, as if to a non-technical friend how to actually pronounce “NGINX”, and why an org might chooose to use it.
- NGINX is pronounced as "engine-x" (like "engine" with an "X" at the end).
- An organization might choose to use NGINX due to its efficiency in handling web traffic, improving website performance, and ensuring reliability. NGINX acts like a traffic manager, helping websites handle lots of visitors smoothly without slowing down or crashing. It's chosen because it keeps websites running fast and stable even when there are lots of people visiting the site at the same time.

#### Resources
[ChatGPT] (https://chat.openai.com/share/a3ba0ffe-b837-4bb9-bdbc-8223f58434fa) <br>
[NGINX] (https://www.nginx.com/resources/glossary/nginx/)