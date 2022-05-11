# 3-assignment-Loading Data from External Sources

You can integrate any database with Exasol as long as the external source supports a JDBC interface. You need to upload the corresponding JDBC driver into EXAoperation (see Manage JDBC Drivers) and then use the generic JDBC interface for IMPORT and EXPORT. By supporting native interfaces to Exasol and Oracle databases, we achieve even better performance.

You can load data using the IMPORT and EXPORT statements and combine that with further post-processing through subselects. You can even specify a statement instead of a table name for the external data source which is executed on that system, for example, to load a certain part of a table into Exasol.

This section describes how you can connect to sources with Exasol for importing or exporting of data. 
Reading JSON Files using Pandas

To read the files, we use read_json() function and through it, we pass the path to the JSON file we want to read. Once we do that, it returns a “DataFrame”( A table of rows and columns) that stores data. If we want to read a file that is located on remote servers then we pass the link to its location instead of a local path.

Example 1: Reading JSON file

Python3

import pandas as pd 

  

  

df = pd.read_json("FILE_JSON.json") 

df.head() 

Output:

One Two 0 60 110 1 60 117 2 60 103 3 45 109 4 45 117 5 60 102Example 2: Creating JSON data and reading in dataframe

Here we will create JSON data and then create a dataframe through it using pd.Dataframe() methods.

Python3

import pandas as pd 

  

data = { 

    "One": { 

        "0": 60, 

        "1": 60, 

        "2": 60, 

        "3": 45, 

        "4": 45, 

        "5": 60 
         }, 

    "Two": { 

        "0": 110, 

        "1": 117, 

        "2": 103, 

        "3": 109, 

        "4": 117, 

        "5": 102 

    } 

} 

  

df = pd.DataFrame(data) 

  

print(df)
One Two 0 60 110 1 60 117 2 60 103 3 45 109 4 45 117 5 60 102

Research is an integral part of the marketing of every business. The success of a business depends on the acceptability of the product. Research is used to understand the expectation of the target audience. The outcome of thorough research helps in developing a successful marketing plan.Research can be categorized into two broad categories, primary research and desk research or secondary research.
the definition of desk research, what is desk research, the importance of desk research, reasons to conduct desk research, advantages of desk research, and steps to do desk research.

Research is an integral part of the marketing of every business. The success of a business depends on the acceptability of the product. Research is used to understand the expectation of the target audience. The outcome of thorough research helps in developing a successful marketing plan.Research can be categorized into two broad categories, primary research and desk research or secondary research.
desk is a common part of many work environments, whether hotels, beauty salons, dental offices or educational housing facilities. If you work as a front desk clerk, you're in charge of performing a wide range of tasks. When guests show up at your place of employment, you serve as the introduction to their visit.

Understanding the functions and importance of front office impressions on visitors is key to success in this highly visible role. Other important qualities include friendliness, professionalism and excellent communication skills, according to Appalachian State University.

desk is a common part of many work environments, whether hotels, beauty salons, dental offices or educational housing facilities. If you work as a front desk clerk, you're in charge of performing a wide range of tasks. When guests show up at your place of employment, you serve as the introduction to their visit.

Understanding the functions and importance of front office impressions on visitors is key to success in this highly visible role. Other important qualities include friendliness, professionalism and excellent communication skills, according to Appalachian State University.

Luggage handling, 2) Paging and Message Handling, 3) Delivery of newspaper, 4) Collection of Room Keys at departures, 5) Miscellaneous Jobs

1) Luggage handling:

Luggage handling of the guest is done at a various occasion such as arrival, during stay (change of rooms) and at the time of departure. At the time of arrival when the luggage of the guests moved from car/taxi to the lobby and further to the allotted room, the activity is called "Up bell activity’". When the luggage of the guest is moved from room to lobby and further to the car/taxi at the time of departure the activity is called "down bell activity’".

2) Paging and Message Handling:

Apart from luggage handling the bell desk is also responsible for paging a guest. The paging is a system of locating the guest in the hotel. Many times the in-house guest expects a phone call or a visitor but decides not to wait in the room, and might decide to go to a public area such as bar, restaurant, swimming pool, lobby or lounge etc. of the hotel or may go out of the hotel.

In such cases hotel request the guest to tell about his whereabouts through a location form. This current location of the guest is duly updated on the hotel software under the function called Locator or Traces. In case of hotels who are not using a hotel software this form is usually filled in by the guest but many times it may be filled in by the hotel staff on the instructions of the guest and kept in the room folder. The bell desk’s function is also to handle and distribute mail, couriers and message received by the front desk in the absence of the guests to their respective rooms.

4) Delivery of newspaper:

As per the hotel policy, all hotel guests receive a copy of hotel newspapers each morning. The bellboys in the night shift are responsible for delivering the newspapers to all occupied rooms and the areas of the hotel and also keeping a record of the same is done by the bell desk. The Bell Captain on duty is also responsible to coordinate with the newspaper supplier and order the required number of the newspaper as per the number of the room occupied.

5) Collection of Room Keys at departures:

Another very important function of the bell desk is the collection of room key from a checkout guest and depositing the same at the front desk. Depending upon the types of the key used by the hotel either manual key or key cards the bells desk staff should always keep a watch and remind the guest at departure to deposit the key.

6) Miscellaneous Jobs:

Miscellaneous jobs such as postage stamps handling, postcard, courier collection, taking care of outgoing mail of the guest, first aid box, over the counter medicine kit, carrying out outside errands for the guest and hotel such as serving welcome drinks, buying of cinema tickets, moving of files and documents etc. for the guest as well as going to banks, post office and also uploading or compiling the police report or emigration report.

Features of Cassandra

Apache Cassandra is an open source, user-available, distributed, NoSQL DBMS which is designed to handle large amounts of data across many servers. It provides zero point of failure. Cassandra offers massive support for clusters spanning multiple datacentres. 

There are some massive features of Cassandra. Here are some of the features described below: 

Distributed: 

Each node in the cluster  has same role. There’s no question of failure & the data set is distributed across the cluster but one issue is there that is the master isn’t present in each node to support request for service.Supports replication & Multi data center replication: 

Replication factor comes with best configurations in cassandra. Cassandra is designed to have a distributed system, for the deployment of large number of nodes for across multiple data centers and other key features too.Scalability: 

It is designed to r/w throughput, Increase gradually as new machines are added without interrupting other applications.Fault-tolerance: 

Data is automatically stored & replicated for fault-tolerance. If a node Fails, then it is replaced within no time.MapReduce Support: 

It supports Hadoop integration with MapReduce support.Apache Hive & Apache Pig is also supported.Query Language: 

Cassandra has introduced the CQL (Cassandra Query Language). Its a simple interface for accessing the Cassandra.



