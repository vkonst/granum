# granum
#### Phase 1 submission to IBM "Unchain the Frame" virtual hackathon 2017
04.sep.2017



## Description of Idea

“**Grānum**” is a SaaS service to track bulk commodities through (reusable) RFID tags.<br />
<br />
Many agricultural commodities such as grains, sugar and soybeans are handled in bulk.<br />
Tracking them is done through tracking transportation containers which does not always equal tracking the commodity.<br />
<br />
RFID tags injected into the bulk will provide capability to directly and precisely authenticate commodities along the supply chain from harvesting to processing.<br />
<br />
Cheap and safe RFID tags with unique IDs are evenly introduced into the commodity at the source (when harvesting, loading etc.) and removed immediately before processing.<br />
RFID scanners read tag IDs at key points of loading, storage and processing (elevators, terminal and port conveyors).<br />
The scanned data is immediately recorded onto blockchain.<br />
<br />
In this way scanners read a digital “fingerprint” (unique set of tag IDs) for every batch and the blockchain stores it.<br />
<br />
The service will provide data to existing supply chain management and financial systems.<br />
A supply chain transaction is confirmed not just by paper documents, but with "hard" data on actual content of the batches which can further be linked to testing sheets/quality certificates by laboratories.<br />
<br />
Besides tracking commodities the service will also provide “proof of shipment/delivery” signals for smart contracts or generate alerts.<br />
<br />
Business value -<br />
- increasing trust between farmers, traders, processors and customers through-<br />
.. confirmation of products’ origin and quality<br />
.. reduced risk of fraud, misrepresentation<br />
.. almost real time visibility into supply chain for bulk goods
- cutting overhead via transaction automation<br />

<br />
The following components of IBM Bluemix platform will be used:<br />

- IoT Foundation, Watson IoT – management of scanners, processing raw data<br />
- Hyperledger Fabric – blockchain<br />
- API to banking, financial and retail services<br />
- MEAN stack micro-services in Docker containers on Open Source Cloud Native Workloads<br />
<br />

## Market Understanding and Size
Prospective customers are agricultural commodity traders, facilities operators and processors.<br />
World export of 3 major grain commodities (wheat, rice, corn) is expected to make 360 million tones in 2017/2018 (the world production is much bigger - 2260 tones).<br />
<br />
Providing “Grānum” is used for every second tone of exported grains at US$ 1 per tone, the market size will make US$ 180 millions.

## Go to Market Strategy
International commodity traders and especially major F&A commodities exporters are best suited for the product.<br />
Providers of supply chain management systems (platforms) are considered as prospective partners.

## Monetization Plan
At the beginning, subscription as the main source of revenues, with a couples of paid plans.<br />
Then focus towards more client-tailored services (integration with customers API’s, advanced “Oracles” and smart contact calls, etc.) for premium subscribers and providing basic services for free.

## Product Roadmap
Product Roadmap.odt

## How are you implementing design and usability into your idea?
From the very beginning, focus on:<br />
- needs of the target users<br />
- user productivity<br />
- UX testing and customers feedback
<br />

## Team Profiles

### Vadim Konstantinov
vadim.konstantinov@gmail.com
<br />
https://www.linkedin.com/in/vkonst
<br />
https://github.com/vkonst/
<br />

### Boris Lobzov
boris.lobzov@gmail.com
<br />
https://www.linkedin.com/in/boris-lobzov-3791531/
<br />

### Anatoliy Aksenov
anatoliy@aksenov.org
<br />
https://github.com/AnatoliyAksenov
<br />
