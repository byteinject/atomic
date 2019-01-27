# Atomic Advanced Denial of Service 

## What is Atomic

Atomic is a Denial of Service (DoS) software that performs stress tests 
on servers to evaluate the transmission of data on servers. Packages are 
injected via HTTP protocol directly into the application, multiple 
requests are simultaneously created on the target.

## How to use

* `chmod +x atomic`
* `./atomic --url example.com`

## How it works

1. Starts a targeted HTTP connection.
2. Sends an infinite number of fragmented packets.
3. Deny all incoming HTTP requests resulting in a successful attack.

## Requirements

json (pip install json)
requests (pip install requests)
pysocks (pip install pysocks)

## Bugs report
Email: byteinject@protonmail.com

## License
Code is licensed under the MIT License.


