<!-- $theme: gaia -->

# Check MK

Versatile monitoring solution building on 15+ years of experience

---
# What is Check MK?
* An abstraction on top of Nagios style configuration
* A web interface and an API
* A modern monitoring agent
* A tightly bundled collection of well tested monitoring tools
	* Nagios (or Icinga/Shinken) - Monitoring core
	* PNP4Nagios - Graphs
	* Nagvis - Presentation	
	* LiveStatus - Status API
---
# How can I monitor?
* Check MK agent with _automatic service inventory_ for all major operating systems (Linux, Windows, OS X, AIX etc)
* Network devices via SNMP (w/service discovery)
* Ping
* Active checks - HTTP, SMTP, RDP, SSH etc

---
# What can I monitor?
* Operating systems
* Switches, routers, loadbalancers
  * Networks and network devices
* Web services, mail servers, message queues...
* VMWare, BigIP, Oracle, MySQL, MSSQL, Netscaler, 3Par
  * Just about anything...
---
# Topology and dependencies
* Automatic "parent host scan"
  * Switch outage can generate 1 alert
    * Child hosts depend on the switch
* Service dependency mapping
  * Service X, Y depends on Service Z
---
# BI: Business Intelligence

Build accurate service models
* Map everything that is needed for a service to operate
* Specify dependencies and clusters
* Define criticality of dependencies
  * Application cluster with reduced capacity still gives an operational service
  * Expired SSL certificates does not
---
# Alerting
* Alerts can be sent via mail, SMS, Slack, Opsgenie...
* Hosts/services can have notification periods
  * In example: Notify only between 7-17
* Hosts/service can have service periods
  * Service state ignored outside of 'opening hours'

---
# Reporting
* Availability reports for any service
* Graph reports for given or custom time ranges
* Bundle desired services into one report
* Export reports as PDF

