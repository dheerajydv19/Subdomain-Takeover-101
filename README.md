# Subdomain-Takeover-101
A simple repo for learning about subdomain takeover.

## Authors

- [@dheerajydv19](https://www.twitter.com/dheerajydv19)

Theory - 
https://hacklido.com/blog/315-subdomain-takeover-the-easy-way

  *Note - I won't be writing the theory stuff here since, its already written on my hacklido blog, so read that first using the above link.*


## Tools For Subdomain Enumeration - 
1. [Amass](https://github.com/OWASP/Amass)
  
   Installation - 
   ```bash
   sudo apt install amass
   ```
   Usage - 
   ```bash
   amass enum -d example.com
   ```
2. [subfinder](https://github.com/projectdiscovery/subfinder)
  
   Installation - 
   ```bash
   sudo apt install subfinder
   ```
   Usage - 
   ```bash
   subfinder -d example.com
   ```

3. [knock](https://github.com/guelfoweb/knock)
  
   Installation - 
   ```bash
   git clone https://github.com/guelfoweb/knock.git
   cd knock
   pip3 install -r requirements.txt
   ```
   Usage - 
   ```bash
   python3 knockpy.py example.com
   ```
4. [assetfinder](https://github.com/tomnomnom/assetfinder)
  
   Installation - 
   ```bash
   sudo apt install assetfinder
   ```
   Usage - 
   ```bash
   subfinder -d example.com
   ```

5. [Altdns](https://github.com/infosec-au/altdns)
  
   Installation - 
   ```bash
   sudo apt install altdns
   ```
   Usage - 
   ```bash
   amass enum -d example.com
   ```

8. [TheHarvester](https://github.com/laramies/theHarvester)
  
   Installation - 
   ```bash
   sudo apt install theharvester
   ```
   Usage - 
   ```bash
   amass enum -d example.com
   ```
