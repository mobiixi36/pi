If you want to create self-signed certificates quite often, you can make use of this shell script. You just need to execute the script with the domain name or IP that you want to add to the certificate.

Set the script executable permission by executing the following command.
```
chmod +x self-cert-gen.sh
```

Execute the script with the domain name or IP. For example,
```
./self-cert-gen.sh cows.com
```