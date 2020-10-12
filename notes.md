### PD Notes

```
RAW Consistency - read after write consistency
Example - Once Object is written to s3 via PUT, and reading is always consistent.

Eventual Consistency -  

```

### VPC

![](img/VPC.png)

* VPC
  * Routing Table
  * Natwork ACL
  * Subnet
  * Security Group

* When ever we create a new VPC, a new Route Table Entry, Network ACL, Security Group are created. 
  * **Subnet we have to create Manually for newly created VPC.**
  * **Internet Gateway we also need to create manually, We can only attach one VPC to IG(Internet Gateway)** 

![](img/VPC01.png)

