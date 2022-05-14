To further verify the practicability of Humer, we conduct a case study to check whether the use of Humer can help DL-based vulnerability detectors to discover new vulnerabilities from real-world open source software.
We select seven widely used open source products as our test objects: Git, Httpd, Libav, OpenSSL, Seamonkey, Thunderbird, and Xen.
The selected versions of these products include both several old versions and the latest version.
In this way, we can report whether vulnerabilities in old versions have been "silently" patched in the latest version or not.
The total number of lines of code we analyzed exceeds 58 million lines. 
Through the scanning reports, we finally detect 281 vulnerabilities that are not reported in NVD. Among them, 98 have been "silently" patched by vendors in the latest version of corresponding products, 24 vulnerabilities have been deleted, and the other 159 still exist in the products.
