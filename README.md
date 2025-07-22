# Yet Another Distributed File System (YADFS)

## Overview
YADFS is a lightweight **distributed file system** built using Python and Flask, designed for efficient file storage, retrieval, and fault tolerance. It supports up to **400 files** with metadata management and redundancy to ensure high availability and reliability.

## Key Features
- **Distributed Storage**: Files are split into chunks and stored across multiple nodes.
- **Metadata Management**: Centralized metadata server to track file locations.
- **Fault Tolerance**: Automatic recovery from node failures.
- **REST API Support**: File upload, download, and delete operations.
- **Scalability**: Can scale horizontally by adding storage nodes.

## Tech Stack
- **Languages:** Python  
- **Frameworks:** Flask (for REST API services)  
- **Databases:** SQLite/MySQL (for metadata storage)  
- **Tools:** Docker (optional for containerization)  

## Architecture
1. **Client** – Sends file requests (upload/download).
2. **Metadata Server** – Tracks file chunks and node mapping.
3. **Storage Nodes** – Stores actual file chunks.


