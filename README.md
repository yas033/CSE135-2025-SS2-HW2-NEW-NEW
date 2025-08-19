# cse135-2025-ss2-HW1

## Part 2 ： Deploy from Github
1) create a new pair of ssh key
2) add the new public key to Droplet and the private key to Github Secrets
   

## Step 4: Employ password protection

Login information: 

username:grader
password:8888

username:nicole
password:8888

username:yanhua
password:8888


## Step 5: Compression Verification

Enabled mod_deflate in Apache to compress HTML, CSS, and JS

Verified using Chrome DevTools:

content-encoding: gzip present in Response Headers

HTML reduced in transfer size, confirming that compression is active.

After enable the compression, the HTML file sent from the server became much smaller in size when transferred, but the actual page content stayed the same. The browser still showed the full HTML after it was uncompressed. This made the page load faster and used less data.


## Step 6: Obscure server identity

Hiding server- information or server version can help prevent attackers from accessing your server. This improves security, as clear version information gives hackers a better understanding of where to begin looking for vulnerabilities. I spent a long time working on this part, and we didn't successfully to create a 'server: CSE135 Server'.But I removed the specific Apache version information to minimize risk within my capabilities.

