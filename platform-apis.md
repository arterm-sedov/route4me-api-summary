# Platform APIs

This section provides a brief overview of the Route4Me API endpoints.

For detailed descriptions of each API endpoint, including all parameters, responses, and code examples, see the [**complete API reference**](https://route4me.io/docs/#platform-apis).

For detailed real-world examples addressing various business needs, see the [**API tutorials**](https://route4me.io/tutorials/).&#x20;

The Route4Me API provides a wide range of features for route planning and optimization and logistics management.&#x20;

## Available APIs

### **Optimizations**&#x20;

Create, retrieve, update, and remove optimizations or perform re-optimization.&#x20;

An optimization problem is a set of addresses to visit, and a solution to an optimization problem gives a set of routes based on various constraints for each address and depot.&#x20;

See [**Optimisations API Reference**](https://route4me.io/docs/#optimizations)

### **Routes**

Create, update, search, retrieve, merge, duplicate, resequence, share, and remove routes, or get the schedule calendar.&#x20;

A route is a collection of addresses to be visited by a single vehicle in the optimal sequence within a specific period. The route sequencing depends on the attributes, constraints, and metadata of each address.&#x20;

See [**Routes API Reference**](https://route4me.io/docs/#routes)

### **Orders**

Create, retrieve, update, and remove orders or add them to routes and optimizations.&#x20;

An order is a request for a freight delivery to a party. To improve integration with various e-commerce platforms, Route4Me allows you to get, add, update, and remove custom fields for orders.&#x20;

See [**Orders API Reference**](https://route4me.io/docs/#orders)

### **Addresses**

Mark addresses either as visited, departed, detected as visited, or detected as departed.&#x20;

An address is a location of a stop or destination. It usually contains street name and number, city, state, country, and ZIP Code.&#x20;

See [**Addresses API Reference**](https://route4me.io/docs/#addresses)

### **Geocoding**

Forward geocode, reverse geocode, and batch geocode addresses.&#x20;

Geocoding converts addresses into geographic coordinates to place them as markers on a map or performs the reverse conversion.&#x20;

See [**Geocoding API Reference**](https://route4me.io/docs/#geocoding)

### **Tracking**

Retrieve asset and route tracking data, insert route tracking data, get all user locations, and search user locations.&#x20;

GPS tracking is location surveillance to remotely track an object's coordinates, speed, and course.&#x20;

See [**Tracking API Reference**](https://route4me.io/docs/#tracking)

### **Members**

Create, update, remove, and authenticate users, view account sub-users, validate sessions, register Route4Me accounts, get user details, add custom data to users, or add, retrieve, update, and remove configuration keys in member accounts.&#x20;

A member is an authorized user of the Route4Me API.&#x20;

See [**Members API Reference**](https://route4me.io/docs/#members)

### **Notes**

Add and retrieve route notes, upload note files, add custom notes to routes, or add and retrieve custom route types.&#x20;

A note is a piece of information that is attached to an address or a route.&#x20;

See [**Notes API Reference**](https://route4me.io/docs/#notes)

### **Vehicles**

Create, retrieve, update, and remove vehicles or assign them to routes.&#x20;

A vehicle is a mode of transportation that belongs to an account and is assigned to a route.&#x20;

See [**Vehicles API Reference**](https://route4me.io/docs/#vehicles)

### Commercial Routing

Create trucks in your account and optimize routes for trucking operations.&#x20;

A truck is a large and powerful vehicle that may be configured to mount specialized equipment. Trucking services require special considerations, such as truck size, the presence of hazardous materials, trailer type and parameters, and local transportation rules for trucking.&#x20;

See [**Commercial Routing API Reference**](https://route4me.io/docs/#commercial-routing)

### Activity Feed

Retrieve activities: all or last, related to a team on the route, a user, or a specific event, or log a message to the activity feed (e.g., for two-way chatting).&#x20;

The activity feed is a record of all routing events in your account: route, optimization and address modifications, events related to drivers, and more.&#x20;

See [**Activity API Reference**](https://route4me.io/docs/#activity-feed)

### Address Book

Create, retrieve, update, search, and remove address book locations.&#x20;

An address book is a repository for user locations.&#x20;

See [**Address Book API Reference**](https://route4me.io/docs/#address-book)

### Address Book Group

Create, retrieve, update, and remove groups, or get contacts by group.&#x20;

An address book group is used to search and group the address book contacts.&#x20;

See [**Address Book Group API Reference**](https://route4me.io/docs/#address-book-group)

### Avoidance Zones

Create, retrieve, update, and remove avoidance zones.&#x20;

An avoidance zone is a geographic area to avoid in a route. A user defines the avoidance zones for the optimization algorithm.&#x20;

See [**Avoidance Zones API Reference**](https://route4me.io/docs/#avoidance-zones)

### Territories

Create, retrieve, update, and remove territories.&#x20;

A territory consists of smaller areas that are combined. For instance, a sales territory could be a group of zip code areas, counties, or states, and a school district could be a group of blocks or streets.&#x20;

See [**Territories API Reference**](https://route4me.io/docs/#territories)

### Telematics

Create, retrieve, list, update, and remove telematics connections.&#x20;

A telematics connection links your account in the Operational Assessment system and your telematics vendor. It allows you to import and synchronize the data with telematics vendors such as Verizon Connect, Geotab, Samsara, Azuga, and Fleet Complete.&#x20;

See [**Telematics API Reference**](https://route4me.io/docs/#telematics-connections)
