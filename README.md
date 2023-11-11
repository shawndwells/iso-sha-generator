# iso-sha-generator
Bash script that generates a SHA512 checksum for an ISO file, and recursively of all files it contains.


SAMPLE:
`````bash
./iso-sha-generator ~/Downloads/rhel-8.4-x86_64-boot.iso

mount: /tmp/ckv0d8: WARNING: source write-protected, mounted read-only.
sha512sum of /home/shawn/Downloads/rhel-8.4-x86_64-boot.iso written to /home/shawn/Downloads/rhel-8.4-x86_64-boot.sha512sum
sha512sum of /home/shawn/Downloads/rhel-8.4-x86_64-boot.iso files written to /home/shawn/Downloads/rhel-8.4-x86_64-boot.sha512sum-files
`````````
