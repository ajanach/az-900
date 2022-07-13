# Storage services

## Storage Account:
- group of services which include:
    - blob storage
    - queue storage
    - table storage
    - file storage
- used to store:
    - files
    - messages
    - semi-structured data
- high scalabile (up to petabytes of data)
- highly durable (99.999999999% - 11 nines, up to 16 nines)
- cheapest per GB storage

<img src="..\Images\storageAcc.png" alt="storageAcc.png" />

## Blob Storage:
- BLOB - binary large object - file
- designed for storage of files of any kind
- tree storage tiers:
    - hot: frequiently accessed
    - cool: infrequently accessed data (lower availability, high durability)
    - archive: rarely (if-ever accessed data)

<img src="..\Images\BLOB.png" alt="BLOB.png" />

## Queue Storage:
- storage for small pieces of data (messages)
- designed for scalable asynchronous processing

<img src="..\Images\queueStorage.png" alt="queueStorage.png" />

## Table Storage:
- storage for semi-structured data (NoSQL)
    - no need for foreign joins, foreign keys, relationships or strict schema
    - designed for fast access
- many programming interfaces and SDKs

<img src="..\Images\tableStorage.png" alt="tableStorage.png" />

## File Storage:
- storage for files accessed via shared drive protocols
- designed to extend on-premise file shares or implement lift-and-shift scenarious

<img src="..\Images\fileStorage.png" alt="fileStorage.png" />

## Disk Storage:
- disk demulation in the cloud
- persistent storage for VMs
- different:
    - sizes
    - types (SSD, HDD)
    - performance tiers
disk can be unmanaged or managed

<img src="..\Images\diskStorage.png" alt="diskStorage.png" />
