# The WITS Protocol Standards Organisation and the Lucid Protocol
## The need for a Standard Protocol
All Utilities use telemetry to monitor and control their remote assets. Traditionally, telemetry consists of a “Field Device” which is linked to a “Master Station” using a variety of telemetry protocols and communication methods. This provides data and information for the purpose of monitoring and controlling the process and the associated plant.
Increasingly, utilities are placing more reliance on telemetry to provide the required data both to improve their operational efficiency and customer service.
So there is an increasing need to have common standards for telemetry such that the required data can be collected in the most efficient manner.
The issue facing the utilities industry is that telemetry standards have been driven by individual companies working with their own suppliers. This has led to a wide variety of standards, with equipment from one supplier not being able to communicate with equipment from another.

## The development of the WITS-DNP3 protocol standard
The Worldwide Industrial Telemetry Standards (WITS) group was formed in 2003 with the aim of helping utility companies to become more efficient by encouraging co-operation between utilities and with engineers and consultants in external supplier organisations. The original WITS vision was simple:
 “To harness the combined strengths of knowledge, skills and influence of the water industry through taking responsibility for the continuous improvement of telemetry technology and service, through shared developments on behalf of the UK Water Management organisations.”
The first task was to investigate the potential for standardising telemetry protocols for communications between Field Devices and Master Stations, in order to enable utility companies to move away from being locked into a single supplier. The development of “plug and play” compatibility would be of enormous benefit to both utilities and suppliers. Utility companies would benefit from increased product choice, reduced cost, simpler configuration, an ability to move away from bespoke one supplier systems, and improved data quality. Suppliers would benefit from more market opportunities and the potential to reduce development time.
Hence the WITS-DNP3 Protocol Standard was developed. This was based on the internationally recognised DNP3 standard which was already in use across the world. However in order to achieve the vision of ‘plug and play’, the functionality which the protocol embraced needed to be defined very specifically, and it also needed to initially meet the requirements of the UK water industry.
This was carried out by producing a detailed set of Application Notes which specify the required functionality of the Protocol, along with a defined testing regime.

## The WITS Protocol Standards Association
Once the Standard was produced, attention turned to its sustainability. To ensure this the WITS Protocol Standards Association (PSA) was established and currently provides for the maintenance and management of the WITS-DNP3 protocol. The PSA has ownership of the Standard and also the responsibility to ensure it continues to meet the requirements of the utilities industry.
It now has over 80 members mainly from the UK but also with a growing number from overseas. Our ultimate aim is to spread the adoption and usage of the WITS Protocols worldwide.

## Enter Lucid
Lucid adds functionality for the management of data gathering and control devices, providing a rich set of functions which were previously implemented in telemetry and remote SCADA systems using manufacturer-specific protocols.
By implementing a common standard, Lucid Protocol users can purchase and operate data sources (‘remote terminal units’ or ‘outstations’, known as Field Devices) and server software (‘data gatherer’, ‘SCADA Server’, ‘Master Station’, known as Supervisory Applications) from multiple vendors and be assured that they will be compatible. This encourages competition between vendors and reduces the costs of procurement, training, operations, and maintenance.
Lucid does not include industry-specific features. The protocol can be used in any industry for the management of remote data gathering and control devices.
Goals for Lucid include:
*	Simple to implement (built on standard protocols, techniques, and libraries).
*	Make efficient use of network resources (needs to work in all common situations from application to application transferring thousands of packets per minute, down to tiny devices using unreliable slow connections).
*	Has a flexible architecture (device to a single or multiple applications and a wide variety of communications scenarios).
*	Maintains common outstation and data logging functionality (with smallest cost to implement, and allow existing WITS systems to share operating philosophy).
*	Economic to maintain validation (simple to test and assure functionality and compatibility).
*	Security (there is a separate Lucid Protocol Security document).
