# VPC-VIRTUAL PRIVATE CLOUD
VPS stands for virtual private cloud.is a logically isloated network from  another virtual network in the AWS cloud .
TYPES OF VPC:
    1.DEFALUT VPC
    2.NON DEFALUT VPC
components of  aws vpc
*ROUTE TABLE:In aws VPC route tables are the set of rules ,that are  used to  determine where the network  traffic has to be directed

*SUBNET:It is a portion of the network that shares a common address have the same prefix are in the same subnet .
2 types of subnets:
            private
            public
*NAT GATEWAY: it updates the routing  of the private subnet such that it sends the traffic to the nat gateway.
*Internet gate way: IGM  allows both inbound and out bound access to the internet.
* security groups: it is a set of firewall rules that controls the traffic for your instances.
* network access control lists: which are state ful and automatically allow return  traffic  for allowed inbound traffic,network ACLS are stateless. it means you must define rules for both inbound and outbound traffic sepearately.
* VPC ENDPOINTS:VPC endpoints allow  private connection between your vpc and other vpc services without using the internet.
* PEERING CONNECTIONS: A vpc peering conneections helps you facilaitate the trasfer of data.
