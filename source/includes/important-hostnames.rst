.. important:: 

   To avoid configuration updates due to IP address changes, use DNS
   hostnames instead of IP addresses. It is particularly important to
   use a DNS hostname instead of an IP address when configuring replica
   set members or sharded cluster members.

   Use hostnames instead of IP addresses to configure clusters across a
   split network horizon. Starting in MongDB 5.0, nodes that are only
   configured with an IP address will fail startup validation and will
   not start.

