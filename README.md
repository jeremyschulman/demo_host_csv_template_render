# Demo: Jinja2 Template Build Cisco configs 

Very often people will have a CSV data file that has a number of fields in it.  The general use-case is to use this data to template build multiple host-specific configurations.  Often times the data provided in the CSV needs to be "transformed" in some way before it can be used for template building.

In this demo the CSV file has a number of fields called `vlan_name_<n>` and `vlan_id_<n>`, where <n> is some number.  The goal is to only use vlans that have a vlan name != 0.

# Try it out

````shell
> python render.py
````
