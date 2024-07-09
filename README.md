# treequeue-mikrotik-cacti
It’s not the first time tutorial about graphing mikrotik queue simple with cacti, you can saw many tutorial about it.  I just republish, howto we use this on your cacti server monitoring. before, I was read that tutorial at forum.cacti.net, and they publish some script cacti for graphing mikrotik queue.

# A. Graphing Mikrotik Queue Tree with Cacti

you will see this files in your extract directory :
cacti_data_query_mikrotik_simple_queue.xml,
cacti_data_template_mikrotik_simple_queue.xml,
cacti_graph_template_mikrotik_simple_queue.xml,
cacti_host_template_mikrotik_queue.xml,
ipacmikro.xml

# B. Installation

Import cacti_data_query_mikrotik_simple_queue.xml (login cacti as administrator),
Import cacti_data_template_mikrotik_simple_queue.xml,
Import cacti_graph_template_mikrotik_simple_queue.xml,
Import cacti_host_template_mikrotik_queue.xml,
Copy ipacmikro.xml to /usr/share/cacti/resource/snmp_queries/ on the Cacti server (ubuntu server).
